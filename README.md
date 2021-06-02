# simple_deadLine_script
JavaScript / jQuery to get the initial date  from HTML and calculate the difference after 7 days from the initial date


![screen1](example12.JPG)
![screen2](example13.JPG)
![screen3](example3.JPG)


# another roun
```
   const speicalRound = (number)=> {
   
     let resultFirst;
     let resultSecond;
     let ournumber = number;
     let numString = number.toString();     
     let splitedNumber = numString.split(".");
 
     let firstNumberString = splitedNumber[0];
     let secondNumberString = splitedNumber[1];
     
     let firstNumber = parseInt(firstNumberString);
     let secondNumber = parseInt(secondNumberString);
     
     if (secondNumber >= 1) {
        resultFirst = firstNumber + 1;
        return resultFirst;
     } else {
        resultFirst = firstNumber;
        return resultFirst;
     }
     
   };
   
   ```
