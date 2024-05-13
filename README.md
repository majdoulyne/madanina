# madanina
calculatrice 

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Calculator</title></head>
<link rel="stylesheet" href="rose.css">
<script LANGUAGE="Javascript" src="rose.js"></script>
<body>
<fieldset>
<h2>Calculator</h2>
<table>
    <tr>
        <td colspan="4"><input type="text" id="text" readonly></td>
    </tr>
    <tr>
        <td><input type="button" value="7" onclick="play('7')"></td>
        <td><input type="button" value="8" onclick="play('8')"></td>
        <td><input type="button" value="9" onclick="play('9')"></td>
        <td><input type="button" value="/" onclick="play('/')"></td>
    </tr>
    <tr>
        <td><input type="button" value="4" onclick="play('4')"></td>
        <td><input type="button" value="5" onclick="play('5')"></td>
        <td><input type="button" value="6" onclick="play('6')"></td>
        <td><input type="button" value="*" onclick="play('*')"></td>
    </tr>
    <tr>
        <td><input type="button" value="1" onclick="play('1')"></td>
        <td><input type="button" value="2" onclick="play('2')"></td>
        <td><input type="button" value="3" onclick="play('3')"></td>
        <td><input type="button" value="-" onclick="play('-')"></td>
    </tr>
    <tr>
        <td><input type="button" value="0" onclick="play('0')"></td>
        <td><input type="button" value="." onclick="play('.')"></td>
        <td><input type="button" value="=" onclick="calculateDisplay()"></td>
        <td><input type="button" value="+" onclick="play('+')"></td>
    </tr>
    <tr>
        <td colspan="4"><input type="button" value="reset" onclick="clearD()"></td>
    </tr>
</table></fieldset>
</body>
</html>

// css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color:rgb(197, 72, 139);
    margin-left:200px;
    margin-right:200px;


}

table {
    margin: 0 auto;
}

td {
    padding: 10px;
}

input[type="button"] {
    width: 100%;
    padding: 20px;
    font-size: 25px;
    background-color:rgb(252, 75, 240);
    border: 150px;

    border-radius: 8px;
    border-width: 15px;
    box-shadow: 5px 5px 25px rgb(126, 10, 72);

}

input[type="text"] {
    width: 85%;
    font-size: 18px;
    border-radius: 2px;
    margin-bottom: 10px;
    padding: 20px ;
    height: 20px;
    border: none;
    background-color: #f7b0db;
    box-shadow: 5px 5px 25px rgb(16, 16, 16);
}

input[type="button"]:hover {
    border-width: 15px;
    box-shadow: 3px 5px 1px rgba(0, 0, 0, 0.44);
}
fieldset{
    display: block;
    margin-right: 350px;
    margin-left: 350px;
    color: rgb(9, 2, 16);

}



