# Vityarthi-Assignment
This project is a collection of Python functions implementing various concepts, properties, and algorithms from elementary number theory. It serves as a comprehensive toolset for exploring the characteristics of integers, including factorization, primality testing, sequence generation, and number classification. 
# 🔢 Number Theory Algorithms in Python

## 💡 Overview of the Project

This project is a collection of Python functions implementing various concepts, properties, and algorithms from **elementary number theory**. It serves as a comprehensive toolset for exploring the characteristics of integers, including factorization, primality testing, sequence generation, and number classification. The primary goal is to provide **efficient and accurate solutions** for classic number theory problems.

---

## ✨ Features

[cite_start]The project implements a wide range of features related to number properties and sequence generation[cite: 1, 2, 4, 6, 8, 10, 42, 46]. The following is a categorized list of the implemented functions based on the assignments:

### **Basic Number Properties & Classification**
* [cite_start]`factorial(n)`: Calculates $n!$[cite: 1].
* [cite_start]`is_palindrome(n)`: Checks if a number reads the same forwards and backwards[cite: 1].
* [cite_start]`mean_of_digits(n)`: Returns the average of all digits in a number[cite: 1].
* [cite_start]`digital_root(n)`: Finds the single-digit sum obtained by repeatedly summing digits[cite: 1].
* [cite_start]`is_harshad(n)`: Checks for Harshad (Niven) numbers (divisible by the sum of its digits)[cite: 1].
* [cite_start]`is_automorphic(n)`: Checks if a number's square ends with the number itself[cite: 1].
* [cite_start]`is_pronic(n)`: Checks if a number is the product of two consecutive integers[cite: 1].
* [cite_start]`is_perfect_power(n)`: Checks if a number can be expressed as $a^b$ where $a>0$ and $b>1$[cite: 19].

### **Divisibility & Factorization**
* [cite_start]`prime_factors(n)`: Returns the list of prime factors of a number[cite: 1].
* [cite_start]`count_distinct_prime_factors(n)`: Counts the number of unique prime factors a number has[cite: 1].
* [cite_start]`count_divisors(n)` (or $d(n)$): Returns the total number of positive divisors[cite: 1].
* [cite_start]`aliquot_sum(n)`: Returns the sum of all proper divisors (divisors less than $n$)[cite: 1].
* [cite_start]`is_abundant(n)`: Checks if the aliquot sum is greater than $n$[cite: 1].
* [cite_start]`is_deficient(n)`: Checks if the aliquot sum is less than $n$[cite: 1].
* [cite_start]`are_amicable(a, b)`: Checks if two numbers are amicable[cite: 1].

### **Primality & Advanced Algorithms**
* [cite_start]`is_prime_power(n)`: Checks if a number can be expressed as $p^k$ where $p$ is prime and $k\ge1$[cite: 1].
* [cite_start]`is_mersenne_prime(p)`: Checks if $2^p - 1$ is a prime number (given that $p$ is prime)[cite: 1].
* [cite_start]`twin_primes(limit)`: Generates all twin prime pairs up to a given limit[cite: 1].
* [cite_start]`is_carmichael(n)`: Checks if a composite number $n$ satisfies $a^{n-1} \equiv 1 \pmod{n}$ for all $a$ coprime to $n$[cite: 31, 35, 43].
* [cite_start]`is_prime_miller_rabin(n, k)`: Implements the **probabilistic Miller-Rabin primality test** with $k$ rounds[cite: 45, 48].
* [cite_start]`pollard_rho(n)`: Implements **Pollard's rho algorithm** for integer factorization[cite: 39, 48].

### **Sequences & Series**
* [cite_start]`lucas_sequence(n)`: Generates the first $n$ **Lucas numbers** (starts with 2, 1)[cite: 17].
* [cite_start]`collatz_length(n)`: Returns the number of steps for $n$ to reach 1 in the **Collatz conjecture**[cite: 25].
* [cite_start]`polygonal_numbers(n, s)`: Returns the $n$-th $s$-gonal number (polygonal number)[cite: 26, 27].
* [cite_start]`multiplicative_persistence(n)`: Counts the steps until a number's digits multiply to a single digit[cite: 1].
* [cite_start]`is_highly_composite(n)`: Checks if a number has more divisors than any smaller number[cite: 1].

### **Advanced Mathematical Functions**
* [cite_start]`mod_exp(base, exponent, modulus)`: Efficiently calculates **Modular Exponentiation** $(\text{base}^{\text{exponent}}) \pmod{\text{modulus}}$[cite: 20].
* [cite_start]`zeta_approx(s, terms)`: Approximates the **Riemann zeta function** $\zeta(s)$ using the first 'terms' of the series[cite: 49].
* [cite_start]`partition_function(n)` (or $p(n)$): Calculates the number of distinct ways to write $n$ as a sum of positive integers[cite: 55].

---

## 🛠️ Technologies/Tools Used

* **Language:** Python 3.x
* **Version Control:** Git
* **Hosting:** GitHub (assumed)

---

## 🚀 Steps to Install & Run the Project

### **1. Clone the Repository**

Open your terminal or command prompt and clone the project:

```bash
git clone [https://github.com/your-username/number-theory-algorithms.git](https://github.com/your-username/number-theory-algorithms.git)
cd number-theory-algorithms
