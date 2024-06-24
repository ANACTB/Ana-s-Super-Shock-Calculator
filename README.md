<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora da Ana Superchoque</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="fundo">
        <h1>Tempestade</h1>
        <h2>Calculadora da Ana</h2>
        <div class="calculadora">
            <p id="resultado">0</p>
            <table>
                <tr>
                    <td><button onclick="clearDisplay()">C</button></td>
                    <td><button onclick="deleteLast()">&lt;</button></td>
                    <td><button onclick="appendToDisplay('/')">/</button></td>
                    <td><button onclick="appendToDisplay('*')">x</button></td>
                </tr>
                <tr>
                    <td><button onclick="appendToDisplay('7')">7</button></td>
                    <td><button onclick="appendToDisplay('8')">8</button></td>
                    <td><button onclick="appendToDisplay('9')">9</button></td>
                    <td><button onclick="appendToDisplay('-')">-</button></td>
                </tr>
                <tr>
                    <td><button onclick="appendToDisplay('4')">4</button></td>
                    <td><button onclick="appendToDisplay('5')">5</button></td>
                    <td><button onclick="appendToDisplay('6')">6</button></td>
                    <td><button onclick="appendToDisplay('+')">+</button></td>
                </tr>
                <tr>
                    <td><button onclick="appendToDisplay('1')">1</button></td>
                    <td><button onclick="appendToDisplay('2')">2</button></td>
                    <td><button onclick="appendToDisplay('3')">3</button></td>
                    <td rowspan="2"><button onclick="calculateResult()">=</button></td>
                </tr>
                <tr>
                    <td><button onclick="appendToDisplay('0')">0</button></td>
                    <td><button onclick="appendToDisplay('.')">,</button></td>
                    <td colspan="2"></td>
                </tr>
            </table>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
