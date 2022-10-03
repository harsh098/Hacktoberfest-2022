# Program

## Question
> Write a program that will print fibonacci series upto N

## Solution
> Range = int(input("How many terms? "))
>
> ### first two terms are pre-Define
> 
> n1, n2 = 0, 1
> 
> count = 0
> 
> ### check if the number of terms is valid
> if Range <= 0:
>
>   print("Please enter a positive integer")
>
> ### if there is only one term, return n1
>
> elif Range == 1:
>
>   print("Fibonacci sequence upto", Range, ":")
>
> print(n1)
> 
> ### generate fibonacci sequence
>
>else:
>
>  print("Fibonacci sequence:")
>
>  while count < nterms:
>
>    print(n1)
>
>    nth = n1 + n2
>      
>    ### update values
>      
>    n1 = n2
>      
>    n2 = nth
>      
>    count += 1
