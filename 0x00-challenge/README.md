<h1 align="center">0X00. FIX MY CODE</h1>
This project is all about finding out what's wrong with an existing code base and fixing it. Download this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge">repository</a> and use it as initial files for all your solutions. <br />
Don't recode everything, just <strong>fix it</strong>!
<br /><br />
<h2>Requirements</h2>
<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code>.</li>
<li>All your files will be compiled on Ubuntu 20.04 LTS.</li>
<li>All your files should end with a new line.</li>
<li>A <code>README.md</code> file, at the root of the folder of the project is mandatory.</li>
</ul>


<h1 align="center">Tasks</h1>

<!-- Task 0 Start -->
<h2>0. FizzBuzz</h2>
Please take a look at this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/0-fizzbuzz.py">source code</a>, which is an implementation of FizzBuzz in Python. Something is wrong... 
<br /><br />

```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```

```15``` should print ```FizzBuzz``` not ```Fizz```... Fix the code. <br />
File: <a href="https://github.com/GM-Samuelstein/Fix_My_Code_Challenge/blob/main/0x00-challenge/0-fizzbuzz.py">0-fizzbuzz.py</a>
<!-- Task 0 End -->

<!-- Task 1 Start -->
<h2>1. Print square</h2>
Please take a look at this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/1-print_square.js">source code</a>, which is an implementation of printing a square in Javascript. Something is wrong... 
<br /><br />

```
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
<code>./1-print_square.js 10</code> should print a square of size 10… Fix the code. <br />
File: <a href="https://github.com/GM-Samuelstein/Fix_My_Code_Challenge/blob/main/0x00-challenge/1-print_square.js">1-print_square.js</a>
<!-- Task 1 End -->

<!-- Task 2 Start -->
<h2>2. Sort</h2>
Please take a look at this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/2-sort.rb">source code</a>, which is an implementation of sorting arguments in Ruby. Something is wrong... 
<br /><br />

```
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
The output is not properly sorted... Fix the code. <br />
File: <a href="https://github.com/GM-Samuelstein/Fix_My_Code_Challenge/blob/main/0x00-challenge/2-sort.rb">2-sort.rb</a>
<!-- Task 2 End -->

<!-- Task 3 Start -->
<h2>3. User password</h2>
Please take a look at this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/blob/master/3-user.py">source code</a>, which is an implementation of a User class in Python. Something is wrong... 
<br /><br />

```
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```
The tests should not print any error… Fix the code. <br />
File: <a href="https://github.com/GM-Samuelstein/Fix_My_Code_Challenge/blob/main/0x00-challenge/3-user.py">3-user.py</a>
<!-- Task 3 End -->

<!-- Task 4 Start -->
<h2>4. Double linked list</h2>
Please take a look at this <a href="https://github.com/holbertonschool/0x00-Fix_My_Code_Challenge/tree/master/4-delete_dnodeint">source code</a>, which is an implementation of a Double linked list in C . Something is wrong... 

```
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
This doesn't look right... Fix the code. <br />
Folder: <a href="https://github.com/GM-Samuelstein/Fix_My_Code_Challenge/tree/main/0x00-challenge/4-delete_dnodeint">4-delete_dnodeint/</a>
<!-- Task 4 End -->

<h2>Author</h2>
"You are free to use the code, but write your own README!" <br /> GM-Samuelstein
