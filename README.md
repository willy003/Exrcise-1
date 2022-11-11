# Exercise-1<br>
a) Output Sequence<br>
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
Fizzbuzz
16
17
Fizz
19
Buzz
Fizz
22
23
Fizz
Buzz
26
Fizz
28
29
FizzBuzz


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
