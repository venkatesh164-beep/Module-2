## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
num=int(input())  <br />
rev=0   <br />
temp=num  <br />
while temp>0:  <br />
    rev=(10*rev)+temp%10  <br />
    temp//=10  <br />
if rev==num:  <br />
    print("The given number {} is a Palindrome".format(num))  <br />
else:  <br />
    print("The given number {} is not a palindrome".format(num))
## Output
<img width="604" height="163" alt="image" src="https://github.com/user-attachments/assets/32a589cd-1d73-4a94-ae6e-cee1701c1b88" />


## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
