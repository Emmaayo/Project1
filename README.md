<!DOCTYPE html>
<html>
    <head>
        <title>protecf</title>
    </head>
    <body>
        <h1>Digital caculator</h1>
         <div class="formstyle">
             <form name="form1">
             <input id="calc" type="text" name="answer">
             <br>
             <br>
             <input type="button" value="1" onclick="form1.answer.value += '1'">
             <input type="button" value="2" onclick="form1.answer.value += '2'">
             <input type="button" value="3" onclick="form1.answer.value += '3'">
             <input type="button" value="+" onclick="form1.answer.value += '+'">
            <input type="button" value="4" onclick="form1.answer.value += '4'">
            <input type="button" value="5" onclick="form1.answer.value += '5'">
            <input type="button" value="6" onclick="form1.answer.value += '6'">
            <input type="button" value="-" onclick="form1.answer.value += '-'">
            <input type="button" value="7" onclick="form1.answer.value += '7'">
            <input type="button" value="8" onclick="form1.answer.value += '8'">
            <input type="button" value="9" onclick="form1.answer.value += '9'">
            <input type="button" value="*" onclick="form1.answer.value += '*'">
            <input type="button" value="/" onclick="form1.answer.value += '/'">
            <input type="button" value="0" onclick="form1.answer.value += '0'">
            <input type="button" value="." onclick="form1.answer.value += '.'">
            <input type="button" value="=" onclick="form1.answer.value=eval(form1.answer.value)">
            <br>
            <input type="button" value="clear all" onclick="form1.answer.value =' '" id="clear">
            <br>
             </form>
             </div>
             </body>
             </html>
