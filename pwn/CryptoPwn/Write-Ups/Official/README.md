# Intro

The intended solution is in this [folder][1]

Run `s.sh` to solve.


# Solution

- The first part of this challenge is about exploiting the encryption scheme
  - It's easy but not easy if you didn't notice that 
    - we don't need to recover the key
    - The only thing we need is choosing the correct plaintext in 5 candidates.
  - The vulnerability is that the key is used several times
  - So we can build a filter to eliminate the wrong answers
  - The left one is the correct answer
  - Read my source code to know more about it
- The second part is exploiting
  - We can set the randomness to a big number so there would be buffer overflow
  - Overwrite some important pointers on heap and get the shell




[1]: ./solution

