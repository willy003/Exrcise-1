# Exrcise-1
a) Output Sequence
1         11         Fizz
2         Fizz       22
Fizz      13         23
4         14         Fizz
Buzz      FizzBuzz   Buzz
Fizz      16         26 
7         17         Fizz
8         Fizz       28
Fizz      19         29 
Buzz      Buzz       FizzBuzz

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
