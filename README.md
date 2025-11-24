Title
Number Theory Utility Suite in Python

Overview
This project is a collection of simple Python programs that perform various number theory calculations and analyses. It includes factorial calculations, palindrome testing, abundant number checks, prime testing with Miller-Rabin, modular arithmetic utilities, and more. It also provides performance metrics like execution time and memory usage for many functions to help understand efficiency.

Features
Compute factorial, palindrome check, abundant/deficient/Harshad number tests

Calculate digital root, mean of digits, aliquot sums, and multiplicative persistence

Prime-related tests: prime power, Mersenne prime, Carmichael number, Miller-Rabin primality

Modular arithmetic functions: modular exponentiation, modular inverse, Chinese Remainder Theorem

Number property tests: automorphic, pronic, Fibonacci, highly composite, perfect power, etc.

Factorization using Pollard’s Rho algorithm and prime factor listing

Additional utilities: Lucas sequence generation, partition function, zeta function approximation

Technologies / Tools Used
Programming Language: Python 3

Standard libraries: time (performance timing), sys (memory usage), math (mathematical functions), random (randomized algorithms), tracemalloc (memory tracking)

No external libraries needed, runs purely on Python standard library

Steps to Install & Run the Project
Install Python 3 from python.org or your system’s package manager

Download and save the project file CSE-PROJECT.py

Open a terminal/command prompt and navigate to the file’s directory

Run the script with python CSE-PROJECT.py or python3 CSE-PROJECT.py

Follow input prompts for test cases (some functions request integer input)

View results and performance metrics printed to the console

Instructions for Testing
Test error handling by inputting invalid values where applicable (e.g., negative input for factorial)

Verify correctness for small, known cases such as factorial(5)=120, palindrome("121")=True

Test special number checks with known examples: 12 (abundant), 8 (deficient), 25 (automorphic)

Run Miller-Rabin on primes like 53 and composites like 51 to see probabilistic primality results

Use modular exponentiation and inverse functions with small numbers to verify outputs

Compare partition function results with documented counts for small n (e.g., p(5)=7)

Check execution time and memory outputs for larger values to see efficiency constraints
