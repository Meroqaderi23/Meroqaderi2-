
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Calculator</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>
<body>
  <div class="calculator">
    <input type="text" id="display" readonly>
    <div class="buttons">
      <button onclick="clearDisplay()">C</button>
      <button onclick="appendNumber('7')">7</button>
      <button onclick="appendNumber('8')">8</button>
      <button onclick="appendNumber('9')">9</button>
      <button onclick="appendOperator('+')">+</button>
      <button onclick="appendNumber('4')">4</button>
      <button onclick="appendNumber('5')">5</button>
      <button onclick="appendNumber('6')">6</button>
      <button onclick="appendOperator('-')">-</button>
      <button onclick="appendNumber('1')">1</button>
      <button onclick="appendNumber('2')">2</button>
      <button onclick="appendNumber('3')">3</button>
      <button onclick="appendOperator('*')">×</button>
      <button onclick="appendNumber('0')">0</button>
      <button onclick="appendNumber('.')">.</button>
      <button onclick="calculate()">=</button>
      <button onclick="appendOperator('/')">/</button>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
