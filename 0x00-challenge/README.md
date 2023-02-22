# 0x00. Fix my code

## Tasks

+ [x] 0. FizzBuzz<br/>_**[0-fizzbuzz.py](0-fizzbuzz.py)**_ fixed implemetation of [this](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py) program in which `15` should print `FizzBuzz` not `Fizz`.<br/>Error below:
```bash
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
+ [x] 1. Print square<br/>_**[1-print_square.js](1-print_square.js)**_ fixed implementation of [this](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js) program in which `./1-print_square.js 10` should print a square of size 10...<br/>Error Below:
```bash
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```
+ [ ] 2. Sort<br/>_**[2-sort.rb](2-sort.rb)**_ fixed sorting implementation of [this](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb) program.<br/>Error Below:
```shell
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```
+ [x] 3. User password<br/>_**[3-user.py](3-user.py)**_ makes tests should not print any error…: [source code](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/3-user.py)<br/>Error below:
```shell
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```
+ [x] 4. Double linked list**[4-delete_dnodeint](4-delete_dnodeint/)**_ contains a functions that fixed implementation of doubly linked list: [source code](https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint).<br/>Error Below:
```shell
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```

