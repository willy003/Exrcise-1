# Exercise-1<br>
a) Output Sequence<br>
1<br>
2<br>
Fizz<br>
4<br>
Buzz<br>
Fizz<br>
7<br>
8<br>
Fizz<br>
Buzz<br>
11<br>
Fizz<br>
13<br>
14<br>
Fizzbuzz<br>
16<br>
17<br>
Fizz<br>
19<br>
Buzz<br>
Fizz<br>
22<br>
23<br>
Fizz<br>
Buzz<br>
26<br>
Fizz<br>
28<br>
29<br>
FizzBuzz<br>


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
6) Increment the number by 1<br>

c) Code<br>
     <?php<br>
   for($i=1;$1<=30;$i++)<br>
   {<br>
   if($i%3==0 && $i%5==0)<br>
   {<br>
     echo "FizzBuzz";<br>
   }<br>
   else if($i%3==0)<br>
   {<br>
     echo "Fizz";<br>
   }<br>
   else if($i%5==0)<br>
   {<br>
     echo "Buzz";<br>
   }<br>
   else<br>
   {<br>
      echo "$i";<br>
   }<br>
}<br>
?>
