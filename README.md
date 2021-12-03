<!DOCTYPE html>
<html>
<head>
    <title>спписок</title>
</head>
<body>
    <script>
        function koment(){ 
            alert ("Вы уверены?");
            var vvod = document.getElementById("pole");
            var vivod = document.getElementById("slovo");
            vivod.innerHTML = vivod.innerHTML + '\n' + vvod.value;
            
        }
    </script>
    
    <p>пиши коментарии </p>
    <br/>
    <input type="text" value="коментарий" id="pole"/>
    <br/>
    <input type="button" value="добавить коментарий" onclick="koment()"/>
    <br/>
    <p id="slovo"></p>
</body>





</html>
