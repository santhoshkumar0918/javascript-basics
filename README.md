<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <input type="checkbox" id="myCheckBox" name="card">
    <label for="myCheckBox">subscribe</label><br><br>

    <input type="radio" id="visaBtn">
    <label for="visaBtn">Visa</label><br><br>
    <input type="radio" id="masterCardBtn">
    <label for="masterCardBtn">MasterCard</label><br><br>
    <input type="radio" id="payPalBtn">
    <label for="payPalBtn">paypal</label><br><br>

    <button type="submit" id="mySubmit">submit</button>

    <p id="subResult"></p>
    <p id="paymentResult"></p>
    <script src="index.js"></script> 
</body>
</html>
