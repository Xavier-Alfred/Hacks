# Starting 
## Trianing for the hackathon
<p>Using the python to find Armstrong number</p>

* Getting a number with input from the user
* Assigning the sum = 0
* Using temporary variable "temp" and assigning it to the input
* Creating a while loop and having condition number is greater than zero
    * Dividing the number by 10 and getting its remainder and storing in a variable
    * Finding the cube of the number and storing in the variable
    * And did the steps till the number is zero
* Checking the the number and the sum,
    * if they are same then the number is Armstrong number.
    * if not, it is not Armstrong number.

### Program

```python
num = int(input("Enter a number: "))
sum = 0
temp=num
while temp > 0:
   digit = temp % 10
   sum += digit ** 3
   temp //= 10

if num == sum:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")
```
* [x] Compiled Succesfully
* [x] Output is verfied
* [ ] For your suggestions 
