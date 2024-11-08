0x03. C - Debugging
===================

-   By Carrie Ybay
-   Ongoing project - started 08-31-2021, must end by 09-03-2021 (in 1 day) - you're done with 0% of tasks.
-   Checker was released at 09-01-2021 12:00 PM
-   QA review fully automated.

Resources
---------

**Read or watch:**

-   [Debugging](https://alx-intranet.hbtn.io/rltoken/faGcpiJiejHH6GhqpmbhUw "Debugging")
-   [Rubber Duck Debugging](https://alx-intranet.hbtn.io/rltoken/RaecqJBNkmZ92vLMpNDuGg "Rubber Duck Debugging")

Debugging is the process of finding and fixing errors in software that prevents it from running correctly. As you become a more advanced programmer and an industry engineer, you will learn how to use debugging tools such as `gdb` or built-in tools that IDEs have. However, it's important to understand the concepts and processes of debugging manually.

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/5/af682f2cbb6d73fd4e42.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU65GPZGY3%2F20210901%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210901T181220Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e1b094ca0dcfc4a561ddbf396c0224cdb014cb52c8d3d03efe6fc24e372e6573)

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/fbQbYSz0Qxw5MEyb6yR05w "explain to anyone"), without the help of Google:

### General

-   What is debugging
-   What are some methods of debugging manually
-   How to read the error messages

Requirements
------------

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files will be compiled on Ubuntu 20.04 LTS using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`
-   All your files should end with a new line
-   Your code should use the `Betty` style. It will be checked using `betty-style.pl` and `betty-doc.pl`
-   A README.md file at the root of the repo, containing a description of the repository
-   A README.md file, at the root of the folder of this project (i.e. `0x03-debugging`), describing what this project is about


Tasks

0. Multiple mains
mandatory
- In most projects, we often give you only one main file to test with.
- Create a file named 0-main.c based on the provided main.c file.
- This file must test that the function positive_or_negative() gives the correct output when given a case of 0.
- You are not coding the solution/function, you're just testing it.
- You can adapt your function from 0x01. C - Variables, if, else, while - Task #0 to compile with this main file to test locally.
- You only need to upload 0-main.c and main.h for this task.
- We will provide our own positive_or_negative() function.
- You are not allowed to add or remove lines of code, you may change only one line in this task.

1. Like, comment, subscribe
mandatory
- Copy the provided main file.
- Comment out (don't delete it!) the part of the code that is causing the output to go into an infinite loop.
- Don't add or remove any lines of code, as we will be checking your line count.
- You are only allowed to comment out existing code.
- You do not have to compile with -Wall -Werror -Wextra -pedantic for this task.
- Fix the print_remaining_days() function so that the output works correctly for all dates and all leap years.
- Line count will not be checked for this task.
- You can assume that all test cases have valid months (i.e., the value of month will never be less than 1 or greater than 12) and valid days (i.e., the value of day will never be less than 1 or greater than 31).
- You can assume that all test cases have valid month/day combinations (i.e., there will never be a June 31st or November 31st, etc.), but not all month/day/year combinations are valid (i.e., February 29, 1991 or February 29, 2427).

2. 0 > 972?
- This program prints the largest of three integers. That's definitely not right.
- Fix the code in 2-largest_number.c so that it correctly prints out the largest of three numbers, no matter the case.
- Line count will not be checked for this task.

3. Leap year
mandatory
- This program converts a date to the day of year and determines how many days are left in the year, taking leap year into consideration.
