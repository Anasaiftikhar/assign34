
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    



    <script>
        // Task 1
        let num1 = parseFloat(prompt("Enter the first number:"));
        let num2 = parseFloat(prompt("Enter the second number:"));
        let sum = num1 + num2;
        alert(The sum of ${num1} and ${num2} is ${sum});

        // Task 2
        let userName = prompt("What is your name?");
        let purchaseAmount = parseFloat(prompt("Enter the total purchase amount:"));
        let discountRate = 10;
        let discountAmount = (purchaseAmount * discountRate) / 100;
        let finalAmount = purchaseAmount - discountAmount;
        alert(${userName}, after a ${discountRate}% discount, your final amount is $${finalAmount.toFixed(2)});

        // Task 3
        let favoriteAnimal = prompt("What is your favorite animal?");
        alert(Wow, ${favoriteAnimal}s are amazing creatures!);
    </script>
</body>
</html>
