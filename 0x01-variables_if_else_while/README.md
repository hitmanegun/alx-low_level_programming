# 0x01. C - Variables, if, else, while

## Tasks
### Task 0
mandatory

This program will assign a random number to the variable n each time it is executed. Complete the source code in order to print whether the number stored in the variable n is positive or negative.

The variable n will store a different value every time you will run this program. You don’t have to understand what rand, srand, RAND_MAX do. Please do not touch this code. The output of the program should be:

    The number, followed by
    if the number is greater than 0: is positive
    if the number is 0: is zero
    if the number is less than 0: is negative
    followed by a new line


Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 0-positive_or_negative.c



### Task 1
mandatory

This program will assign a random number to the variable n each time it is executed. Complete the source code in order to print the last digit of the number stored in the variable n.

The variable n will store a different value every time you run this program. The output of the program should be:

    The string Last digit of, followed by
    n, followed by
    the string is, followed by
    if the last digit of n is greater than 5: the string and is greater than 5
    if the last digit of n is 0: the string and is 0
    if the last digit of n is less than 6 and not 0: the string and is less than 6 and not 0
    followed by a new line

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 1-last_digit.c
    


### Task 2
mandatory

Write a program that prints the alphabet in lowercase, followed by a new line.

You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
All your code should be in the main function
You can only use putchar twice in your code

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 2-print_alphabet.c
    


### Task 3
mandatory

Write a program that prints the alphabet in lowercase, and then in uppercase, followed by a new line.

    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    All your code should be in the main function
    You can only use putchar three times in your code

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 3-print_alphabets.c
    


### Task 4
mandatory

Write a program that prints the alphabet in lowercase, followed by a new line.

    Print all the letters except q and e
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    All your code should be in the main function
    You can only use putchar twice in your code
 
Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 4-print_alphabt.c
    


### Task 5
mandatory

Write a program that prints all single digit numbers of base 10 starting from 0, followed by a new line.

    All your code should be in the main function
 
Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 5-print_numbers.c
    


### Task 6
mandatory

Write a program that prints all single digit numbers of base 10 starting from 0, followed by a new line.

    You are not allowed to use any variable of type char
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    You can only use putchar twice in your code
    All your code should be in the main function

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 6-print_numberz.c
    


### Task 7
mandatory

Write a program that prints the lowercase alphabet in reverse, followed by a new line.

    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    All your code should be in the main function
    You can only use putchar twice in your code

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 7-print_tebahpla.c
    


### Task 8
mandatory

Write a program that prints all the numbers of base 16 in lowercase, followed by a new line.

    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    All your code should be in the main function
    You can only use putchar three times in your code

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 8-print_base16.c
    


### Task 9
mandatory

Write a program that prints all possible combinations of single-digit numbers.

    Numbers must be separated by ,, followed by a space
    Numbers should be printed in ascending order
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    All your code should be in the main function
    You can only use putchar four times maximum in your code
    You are not allowed to use any variable of type char

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 9-print_comb.c
    


### Task 10
#advanced

Write a program that prints all possible different combinations of two digits.

    Numbers must be separated by ,, followed by a space
    The two digits must be different
    01 and 10 are considered the same combination of the two digits 0 and 1
    Print only the smallest combination of two digits
    Numbers should be printed in ascending order, with two digits
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    You can only use putchar five times maximum in your code
    You are not allowed to use any variable of type char
    All your code should be in the main function

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 100-print_comb3.c
    


### Task 11
#advanced

Write a program that prints all possible different combinations of three digits.

    Numbers must be separated by ,, followed by a space
    The three digits must be different
    012, 120, 102, 021, 201, 210 are considered the same combination of the three digits 0, 1 and 2
    Print only the smallest combination of three digits
    Numbers should be printed in ascending order, with three digits
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    You can only use putchar six times maximum in your code
    You are not allowed to use any variable of type char
    All your code should be in the main function
 
Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 101-print_comb4.c
    


### Task 12
#advanced

Write a program that prints all possible combinations of two two-digit numbers.

    The numbers should range from 0 to 99
    The two numbers should be separated by a space
    All numbers should be printed with two digits. 1 should be printed as 01
    The combination of numbers must be separated by comma, followed by a space
    The combinations of numbers should be printed in ascending order
    00 01 and 01 00 are considered as the same combination of the numbers 0 and 1
    You can only use the putchar function (every other function (printf, puts, etc…) is forbidden)
    You can only use putchar eight times maximum in your code
    You are not allowed to use any variable of type char
    All your code should be in the main function

Repo:

    GitHub repository: alx-low_level_programming
    Directory: 0x01-variables_if_else_while
    File: 102-print_comb5.c
