# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
clone the github repository for a standard calculator.

### Step 2:
change settings.py file to allow request from the host.

### Step 3:
Validate the HTML and CSS code.

### Step 4:
Publish the website in the given URL.

## PROGRAM :
<title>SEC Demo on Calculator</title> <style type="text/css"> table{ border: 1px solid
black; margin-left: auto; margin-right: auto; } input[type="text"]{ border: 1px solid black;
padding: 20px 30px; font-size: 24px; font-weight: bold; border-radius: 2px; }
input[type="button"]{
width: 100%;
padding: 20px 40px;
background-color:greenyellow;
border-radius: 2px;
}
</style>
</head>
<body>
<form name="form1" onload="result.value=''">
<h1 style="text-align: center;color:blue;">Simple Calculator</h1>
<table id="calc">
<tr>
<td colspan="4">
<input type="text" id="result">
</td>
</tr>
<tr>
<td><input type="button" value="1"
onclick="result.value+='1'"/></td>
<td><input type="button" value="2"
onclick="result.value+='2'"/></td>
<td><input type="button" value="3"
onclick="result.value+='3'"/></td>
<td><input type="button" value="+"
onclick="result.value+='+'"/></td>
</tr>
<tr>
<td><input type="button" value="4"
onclick="result.value+='4'"/></td>
<td><input type="button" value="5"
onclick="result.value+='5'"/></td>
<td><input type="button" value="6"
onclick="result.value+='6'"/></td>
<td><input type="button" value="-" onclick="result.value+='-
'"/></td>
</tr>
<tr>
<td><input type="button" value="7"
onclick="result.value+='7'"/></td>
<td><input type="button" value="8"
onclick="result.value+='8'"/></td>
<td><input type="button" value="9"
onclick="result.value+='9'"/></td>
<td><input type="button" value="" onclick="result.value+=''"/>
</td>
</tr>
<tr>
<td><input type="button" value="/"
onclick="result.value+='/'"/></td>
5/13/23, 8:54 PM standard-calculator/README.md at main · gracia55/standard-calculator
https://github.com/gracia55/standard-calculator/blob/main/README.md 3/4
'''
OUTPUT:
<td><input type="button" value="0"
onclick="result.value+='0'"/></td>
<td><input type="button" value="."
onclick="result.value+='.'"/></td>
<td><input type="button" value="="
onclick="result.value=eval(result.value)"/></td>
</tr>
<tr>
<td colspan="4">
<input type="button" value="clearall" id="clear"
onclick="result.value=''">
</td>
</tr>
</table>
</form>
</body>
## OUTPUT:


## Result:

