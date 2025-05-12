# HTML
Real Time Temperature Convertor
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Real-Time Temperature Converter</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 50px;
      background: #f4f4f4;
    }
    .container {
      background: white;
      padding: 20px;
      border-radius: 8px;
      max-width: 400px;
      margin: auto;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    input {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      margin-bottom: 20px;
    }
    label {
      font-weight: bold;
    }
  </style>
</head>
<body>

  <div class="container">
    <h2>Temperature Converter</h2>

    <label for="celsius">Celsius (°C):</label>
    <input type="number" id="celsius" placeholder="Enter Celsius">

    <label for="fahrenheit">Fahrenheit (°F):</label>
    <input type="number" id="fahrenheit" placeholder="Enter Fahrenheit">
  </div>

  <script>
    const celsiusInput = document.getElementById('celsius');
    const fahrenheitInput = document.getElementById('fahrenheit
