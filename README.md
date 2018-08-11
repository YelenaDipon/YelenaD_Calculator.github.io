# YelenaD_Calculator.github.io
WebLinkSetUp
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>My Calculator</title>

    <link href="calc.css" rel="stylesheet" type="text/css">
</head>
<h1 id='title'> My 1st Calculator </h1>
<body class='page'>
<input type="text" id="display" readonly>
<br>
<button class='buttons'  id='C'  onclick="digit('  ')">C</button>
<button class='buttons'  id='clear'  onclick="digit('=')">=</button>
<br>
<button class='buttons' onclick='digit(9)'>9</button>
<button class='buttons' onclick='digit(8)'>8</button>
<button class='buttons' onclick='digit(7)'>7</button>
<button class='buttons' class='symbol' onclick="digit('+')">+</button>
<br>
<button class='buttons' onclick='digit(6)'>6</button>
<button class='buttons' onclick='digit(5)'>5</button>
<button class='buttons' onclick='digit(4)'>4</button>
<button class='buttons' onclick="digit('-')">-</button>
<br>
<button class='buttons' onclick='digit(3)'>3</button>
<button class='buttons' onclick='digit(2)'>2</button>
<button class='buttons' onclick='digit(1)'>1</button>
<button class='buttons' onclick="digit('*')">*</button>
<br>
<button class='buttons' onclick="digit('/')">/</button>
<button class='buttons' onclick='digit(0)'>0</button>
<button class='buttons' onclick="digit('.')">.</button>
<script type class="application/javascript" src="calc.js"></script>
</body>
</html>
