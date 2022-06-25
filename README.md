## Welcome to GitHub Pages

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    
</head>
<body>
   
    <script>
         operator= prompt('Enter operator to perform the calculation (Either + - * or /):'); 
        number1 = prompt('Enter the first number');
        number2 = prompt('Enter the second number');

         let result;
         if (operator == '+'){
            result =  parseInt(number1) +  parseInt(number2);
         }
         else if(operator == '-'){
            result = number1 - number2;
         }
         else if (operator == '*'){
            result = number1 * number2;
         }
         else{
            result= number1/number2;
         }
      alert ('Result is ' + result);

    </script>
</body>
</html>
