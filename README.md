# FindingNumber


finding a number
function LargestAndSmallest(arr) {
  var MaxNumber = arr[0],
    MinNumber = arr[0];
  for (var i = 0; i < arr.length; i++) {
    if (arr[i] > MaxNumber) MaxNumber = arr[i];
    else if (arr[i] < MinNumber) MinNumber = arr[i];
  }
  console.log("Maximum Number: " + MaxNumber, "Minimum Number: " + MinNumber);
}
LargestAndSmallest([5, 3, 2, 4, 7, 3, 1, 8, 9]);
