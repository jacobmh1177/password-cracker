# password-cracker
## Introduction
Congrats on finishing the stock-tracker assignment :) For this assignment we will take a small detour
into the more nefarious (and fun) aspects of computer science...hacking! This week you will be 
building a brute-force password cracker. A "brute force" password attack is when a programmer instructs their
computer to try every single possible combination of characters to guess the correct passphrase. You'll
be implementing something very similar this week.

## Problem overview
Your program will start by prompting the user to input his/her password. Once they have done so,
your program will generate random random strings until it "guesses" the user supplied password. 
Thankfully, your password cracker can check to see if it guessed the correct character at each index.
This will enable your program to be much more efficient at cracking the password.

## Required output
You should prompt your user for his/her password and then successively print out the strings your 
program guesses. Once you've cracked the password please print out how many attempts it took for
your program to guess the password.

## Helpful hints
* The python module *random* will be helpful for generating your random strings
* To get user input use the built-in function *raw_input*

