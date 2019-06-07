# Prime Multiplication Table Generator #

## Introduction ##
This is a program that prints out the multiplication table for the first 10 prime numbers. 

## Usage ##

**Using Command-line**

Clone or download this git repository and use `php index.php` to execute the project and show an output.

This project has 3 option settings:

1. If you use `php index.php` it will use the default settings to show a table of prime and it's multiples but with **n=10**.

2. If you use `php index.php <number>` and replace the number placeholder with an integer it will take that as the value of **n**.

3. If you use `php index.php <number> notable` it will print just the first **n** number of primes without multiplication tables.
  
**Using Composer**

In your composer-based php project, run the following line from the command prompt:
```
composer require apsingh/prime-generator
```
This will automatically include the library into the project and you can now access it by including the respective files in your project.

## Sample Output ##

____________________________________________________________________________________

             2      3      5      7     11     13     17     19     23     29
____________________________________________________________________________________

      2      4      6     10     14     22     26     34     38     46     58
____________________________________________________________________________________

      3      6      9     15     21     33     39     51     57     69     87
____________________________________________________________________________________

      5     10     15     25     35     55     65     85     95    115    145
____________________________________________________________________________________

      7     14     21     35     49     77     91    119    133    161    203
____________________________________________________________________________________

     11     22     33     55     77    121    143    187    209    253    319
____________________________________________________________________________________

     13     26     39     65     91    143    169    221    247    299    377
____________________________________________________________________________________

     17     34     51     85    119    187    221    289    323    391    493
____________________________________________________________________________________

     19     38     57     95    133    209    247    323    361    437    551
____________________________________________________________________________________

     23     46     69    115    161    253    299    391    437    529    667
____________________________________________________________________________________

     29     58     87    145    203    319    377    493    551    667    841
____________________________________________________________________________________
