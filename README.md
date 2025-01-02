# codsoft3
<!DOCTYPE html>  
<html lang="en">  
<head>  
<title>Calculator</title>  
<style>  
h1 {  
    text-align: center;  
    padding: 20px;  
    background-color: skyblue;  
    color: white;  
}  

#clear {  
    width: 100px;  
    border: 2px solid gray;  
    border-radius: 3px;  
    padding: 10px;  
    background-color: red;  
}  

.formstyle {  
    width: 150px;  
    height: 310px;  
    margin: auto;  
    border: 3px solid skyblue;  
    border-radius: 5px;  
    padding: 10px;  
}  

input {  
    width: 20px;  
    background-color: rgb(24, 12, 159);  
    color: white;  
    border: 1px solid gray;  
    border-radius: 5px;  
    padding: 5px;  
    margin: 5px;  
    font-size: 14px;  
}  

#calc {  
    width: 100px;  
    border: 2px solid black;  
    border-radius: 3px;  
    padding: 15px;  
    margin: auto;  
}  
</style>  
</head>  
<body>  
<h1>Calculator</h1>  
<div class="formstyle">  
<form name="form1">  
    <input id="calc" type="text" name="answer" disabled> <br><br>  

    <input type="button" value="1" onclick="form1.answer.value += '1'">  
    <input type="button" value="2" onclick="form1.answer.value += '2'">  
    <input type="button" value="3" onclick="form1.answer.value += '3'">  
    <input type="button" value="+" onclick="form1.answer.value += '+'">  
    <br><br>  
    
    <input type="button" value="4" onclick="form1.answer.value += '4'">  
    <input type="button" value="5" onclick="form1.answer.value += '5'">  
    <input type="button" value="6" onclick="form1.answer.value += '6'">  
    <input type="button" value="-" onclick="form1.answer.value += '-'">  
    <br><br>  
    
    <input type="button" value="7" onclick="form1.answer.value += '7'">  
    <input type="button" value="8" onclick="form1.answer.value += '8'">  
    <input type="button" value="9" onclick="form1.answer.value += '9'">  
    <input type="button" value="*" onclick="form1.answer.value += '*'">  
    <br><br>  
    
    <input type="button" value="/" onclick="form1.answer.value += '/'">  
    <input type="button" value="0" onclick="form1.answer.value += '0'">  
    <input type="button" value="." onclick="form1.answer.value += '.'">  
    <input type="button" value="=" onclick="form1.answer.value = eval(form1.answer.value)">  
    <br>  
    
    <input type="button" value="Clear All" onclick="form1.answer.value = ''" id="clear">  
</form>  
</div>  
</body>  
</html>
