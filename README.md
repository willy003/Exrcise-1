# Exrcise-1
a) Output Sequence
1<br>         11<br>         Fizz<br>
2<br>         Fizz<br>       22<br>
Fizz<br>      13<br>         23<br>
4<br>         14<br>         Fizz<br>
Buzz<br>      FizzBuzz<br>   Buzz<br>
Fizz<br>      16<br>         26<br> 
7<br>         17<br>         Fizz<br>
8<br>         Fizz<br>       28<br>
Fizz<br>      19<br>         29<br> 
Buzz<br>      Buzz<br>       FizzBuzz<br>

b) Algorithm
1) Enter the number less or equal to 30
2) Check if the number entered is less than 30
   Yes-> Go to step 3.
   No-> End
3) Check if the number entered is divisible by 3 and 5
   Yes-> Print FizzBuzz and go to step 6
   No-> Go to step 4
4) Check if number is divisible by 3
   Yes-> Print Fizz and go to step 6
   No-> Proceed to next step
5) Check if number is divisible by 5
   Yes-> Print Buzz and go to step 6
   No-> Go to next step
 6) Increment the number by 1
 
 c) Code
 <?php
 for($i=1;$1<=30;$i++)
 {
   if($i%3==0 && $i%5==0)
   {
     echo "FizzBuzz<br>";
   }
   else if($i%3==0)
   {
     echo "Fizz<br>";
   }
   else if($i%5==0)
   {
     echo "Buzz<br>";
   }
   else
   {
      echo "$i";
   }
}
