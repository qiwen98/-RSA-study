# -RSA-study
simple RSA Idea impementation with decimal format 

This project is written in c++ 
This program reads in chunck of strings from txt file (Data.txt) into and encyprted them into a decimal format.
This program contain the way to encryp and decrypt

N refer to P*Q
P refer to random prime number ( range from 1 to 100 inside the program)
Q refer to random prime number ( range from 1 to 100 inside the program) PS: P cannot equal to Q
r refer to Φ(n) = (P-1)(Q-1)
d refer to the provate key calculated using d = (k*Φ(n) + 1) / e

All the variable above will be auto generated.

Expected Input : any combination of paragraphs or chunck of string
Expected outpur: the decimal numbers which represent the encrypted data


