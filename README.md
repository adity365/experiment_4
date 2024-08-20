# BITWISE
## AIM
To study and implement C++ Bitwise Operators

## THEORY
Bitwise operators are fundamental tools in computer programming that allow manipulation of individual bits within binary representations of data. Here's a brief overview of the key concepts:

1. Types of bitwise operators:
   - AND (&)

   - OR (|)
   - XOR (^)
   - NOT (~)
   - Left shift (<<)
   - Right shift (>>)

2. These operators work directly on the binary representation of numbers.

3. They are often used for:
   - Efficient memory usage
   - Low-level device control
   - Cryptography and hashing
   - Optimization in certain algorithms

4. Bitwise operations are typically faster than arithmetic operations.

5. They can be used to perform various tasks like setting/clearing specific bits, checking if a number is odd/even, or multiplying/dividing by powers of 2.

## CODE
```
// Aditya Agarwal
// 23070123162
# include <iostream>
using namespace std;

int main(){
    int a = 3 ;
    int b = 4;
    // Bitwise operators
    cout << "a & b is: " << (a & b) << endl;
    cout << "a | b is: " << (a | b) << endl;
    cout << "~a is: " << (~a) << endl;
    cout << "a ^ b is: " << (a ^ b) << endl;
    
    // left shift and right shift 
    cout << (17>>1) << endl;
    cout <<(17 >> 2) << endl;
    cout << (19 << 1) << endl;
    cout << (21 << 2) << endl;
}
```
## OUTPUT
![image](https://github.com/user-attachments/assets/a15c05eb-ffb4-4918-982d-d805a622780f)

# CONCLUSION

learnt how use bitwise operators in C++.
