# Converting Currency value to Text
A Console Application Program written in C++ Language, which takes in Currency value(Min Value 00, Max Value 9, 99, 99,999.99) as Input and Converts it into words and print out as Text. For ex. If provided "123456.78", it should print out “Rs. One Lakh Twenty Three Thousand Four Hundred And Fifty Six 78/100 ONLY".
# Solution Logic Explanation
The Program Takes Currency Value as Input and takes two functions. One function converts given number into words. It first takes last two digits and passes it to the other function which converts single or two digit numbers into words which takes the exact word for the ones and tens digit number from the arrays which contains the exact words for each number and stores the words in a variable. Then if the number is more than 100 it adds "and" to the variable and again checks the number and takes thousands place numbers and pass it to the other function to convert the number to words and add them to the variable and this process continues for lakhs and crore positions also and prints out the complete text for the numbers with a "Rs." before it. It also checks the number in the decimal part and if it greater than zero, it prints out the decimal part with "/100 ". And Lastly adds"ONLY" to the text. Now you get the currency in words as output.
# Time-Taken
Design-3 hours, Coding-1 hour, Testing-and Fixing-1 hour. Total-Time=5 hours.
# Source code
The main code can be found in [NumberstoText.cpp](https://github.com/afridhasuhaina/Thinkbridge-Assignment/blob/master/NumberstoText.cpp).
# Output Screenshots
The Output ScreenShots can be found in:
[Thousand.png](https://github.com/afridhasuhaina/Thinkbridge-Assignment/blob/master/Thousand.png), 
[Lakh.png](https://github.com/afridhasuhaina/Thinkbridge-Assignment/blob/master/Lakh.png), 
[crore.png](https://github.com/afridhasuhaina/Thinkbridge-Assignment/blob/master/crore.png),
[0 decimal part.png](https://github.com/afridhasuhaina/Thinkbridge-Assignment/blob/master/0%20decimal%20part.png).
