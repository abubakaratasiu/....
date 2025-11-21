<!DOCTYPE html>
<html>
<head>
  <title>ND2A Group -C- Calculator Assignment By Adam Ishaq Adam</title>
  <style>
    body {
      background-color: #ede6e6;
      font-family: Arial;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .calculator {
      background-color: #298949;
      padding: 20px;
      border-radius: 10px;
      width: 320px;
    }
    #display {
      width: 100%;
      height: 50px;
      font-size: 24px;
      text-align: right;
      margin-bottom: 10px;
      padding: 10px;
      border: none;
      border-radius: 5px;
    }
    .buttons {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 10px;
    }
    button {
      height: 50px;
      font-size: 20px;
      border: none;
      border-radius: 5px;
      background-color: #0d0e0d;
      color: rgb(237, 234, 234);
      cursor: pointer;
    }
    button:hover {
      background-color: #258029;
    }
  </style></head>
<body>
  <div class="calculator">
    <input type="text" id="display" disabled>
    <div class="buttons">
      <button onclick="clearDisplay()">C</button>
      <button onclick="appendValue('%')">%</button>
      <button onclick="appendValue('Math.sqrt(')">√</button>
      <button onclick="deleteLast()">⌫</button>

      <button onclick="appendValue('7')">7</button>
      <button onclick="appendValue('8')">8</button>
      <button onclick="appendValue('9')">9</button>
      <button onclick="appendValue('/')">÷</button>

      <button onclick="appendValue('4')">4</button>
      <button onclick="appendValue('5')">5</button>
      <button onclick="appendValue('6')">6</button>
      <button onclick="appendValue('*')">×</button>

      <button onclick="appendValue('1')">1</button>
      <button onclick="appendValue('2')">2</button>
      <button onclick="appendValue('3')">3</button>
      <button onclick="appendValue('-')">−</button>

      <button onclick="appendValue('0')">0</button>
      <button onclick="appendValue('.')">.</button>
      <button onclick="calculate()">=</button>
      <button onclick="appendValue('+')">+</button>
    </div>
  </div>

  <script>
    let display = document.getElementById("display");

    function appendValue(value) {display.value += value;
    }

    function clearDisplay() {
      display.value = "";
    }

    function deleteLast() {
      display.value = display.value.slice(0, -1);
    }

    function calculate() {
      try {
        display.value = eval(display.value);
      } catch (error) {
        display.value = "Error";
      }
    }
  </script>
</body>
</html>

    
  </style>
</head>
<body>


  <div class="group-list">
    <h2>Group C - ND2A (2023/2025)</h2>
    <p>1. ABDULLAHI YAHAYA ABDULLAHI - ND/com/23/0184</p>
    <p>2. ABUBAKAR A TASI'U - ND/com/23/0213</p>
    <p>3. AALIYU MUKHTAR SANI - ND/com/23/0024</p>
    <p>4. ABDULKARIM BUHARI BAGUDU - ND/com/23/0157</p>
    <p>5. SALMAN ASHAFA - ND/com/23/0045</p>
    <p>6. FATIHU SHEHU HASSAN - ND/com/23/0272</p>
    <p>7. ADAM ISHAQ ADAM - ND/com/23/0016</p>
    <p>8. IDAJILI OJIMAOJE ENDURENCE - ND/com/23/0215</p>
    <p>9. HUSSAINI ABDULLAHI - ND/com/23/0096</p>
    <p>10. ISAH ALHASSAN MUKUSIDI - ND/com/23/0134</p>
  </div>

SuperJum
