# RSA Factoring Challenge in C

This README provides an overview of the concepts and steps required to create an RSA Factoring Challenge in C programming.

## 1. Introduction

The RSA Factoring Challenge involves presenting participants with an RSA modulus (n) and challenging them to factor it into its prime factors (p and q). Here are the key concepts and steps:

## 2. Generating RSA Modulus

To create an RSA modulus, you need to:

### 2.1. Generate Large Primes

Use a primality test or random number generator to find two large prime numbers, p and q.

### 2.2. Calculate n

Calculate the modulus n = p * q.

## 3. RSA Factoring Challenge

To create the challenge:

### 3.1. Provide the Modulus (n)

Share the modulus n with participants. It should be a large semiprime number (the product of two prime numbers).

### 3.2. Challenge Participants

Challenge participants to factorize n into its prime factors p and q. They should write a C program to accomplish this.

## 4. Factoring Algorithm

Participants will need to implement a factoring algorithm. The most common algorithm for RSA factoring is Pollard's Rho Algorithm.

## 5. Implementation in C

Participants should implement their factoring algorithm in C:

### 5.1. User Input

- Prompt the user for the value of n (the modulus).
- Ensure proper error handling and input validation.

### 5.2. Factoring Algorithm

- Implement Pollard's Rho Algorithm or another factoring algorithm.
- Iterate until the factors p and q are found.
- Calculate p and q.

### 5.3. Output

- Display the factors p and q once found.
- Ensure readability and clear presentation of the results.

## 6. Testing and Verification

Ensure that the participants' C program correctly factors the provided modulus n into the prime factors p and q.

## 7. Additional Challenges (Optional)

For more advanced challenges:

- Use larger n values to increase the difficulty.
- Add time or resource constraints to make the challenge more interesting.

## 8. Conclusion

Creating an RSA Factoring Challenge in C involves generating a semiprime modulus and challenging participants to factor it. Participants will implement a factoring algorithm in C to find the prime factors p and q. This challenge helps participants practice their cryptography and programming skills.

Feel free to customize the challenge parameters and difficulty levels according to your requirements.

