<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   Project 1: Diagram 01
</head>
<body>
    <h1> A diagram for the API fetching process </h1>
    <p></p>
    <img src="Diagram_1.png" alt="A diagram">
</body>
    <!DOCTYPE html>
<html>
<head>
    <title>API Integration</title>
</head>
<body>
    <div>
        <h1>Crypto Ticker</h1>
        <form id="cryptoForm">
            <label for="crypto">Enter coin name:</label>
            <input type="text" id="crypto" name="crypto">
            <input type="submit" value="Submit">
        </form>
        <div id="cryptoResult"></div>
    </div>
    
    <div>
        <h1>Binance Spot Price</h1>
        <form id="binanceForm">
            <label for="coin">Enter coin symbol:</label>
            <input type="text" id="coin" name="coin">
            <input type="submit" value="Submit">
        </form>
        <div id="binanceResult"></div>
    </div>
    
    <div>
        <h1>Local Business Data</h1>
        <form id="localBusinessForm">
            <label for="business">Enter business keyword:</label>
            <input type="text" id="business" name="business">
            <input type="submit" value="Submit">
        </form>
        <div id="localBusinessResult"></div>
    </div>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="yourScript.js"></script> <!-- replace "yourScript.js" with your actual script filename -->
</body>
</html>
