# sum-of-element-of-given-array
Write a JavaScript program to compute the sum of elements of a given array of integers. 
Code
      <!DOCTYPE html>
<html>
<head>
    <title>Sum of Array Elements</title>
    <script>
        function sumArray(arr) {
            let sum = 0;
            for (let i = 0; i < arr.length; i++) {
                sum += arr[i];
            }
            return sum;
        }

        window.onload = function() {
            const exampleArray = [1, 2, 3, 4, 5];
            const sum = sumArray(exampleArray);
            console.log("The sum of the array elements is: " + sum); // Output: The sum of the array elements is: 15
        }
    </script>
</head>
<body>
    <h1>Check the console for the sum of the array elements</h1>
</body>
</html>
