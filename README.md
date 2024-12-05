# Python-Codes
Performing various python programs. Excited? Let's Begin!

**No.1 WAP to find the roots of the quadratic equation**
https://www.programiz.com/online-compiler/6vCmrfoGWae0g

a) When there are 2 distinct roots
![2 distinct roots](https://github.com/user-attachments/assets/3da54c36-5e41-47e3-a6e8-05a8ea494179)


b) In case of 2 equal roots
![2 equal roots](https://github.com/user-attachments/assets/59ff2a19-adc0-4afb-83c5-01f7a67d42e8)


c) In case of 2 complex roots
![2 complex](https://github.com/user-attachments/assets/20640dcf-540e-40a9-80c1-2f5ea0c56b9d)

**NO.2** WAP TO ACCEPT THE NUMNER 'n' and
https://www.programiz.com/online-compiler/4Cc6XttHFpKiR

j. check if 'n' is prime

![j](https://github.com/user-attachments/assets/90204e5b-b5ba-4dd6-8f89-409fcc3f8ad2)

k. Generate all prime numbers till n

![k](https://github.com/user-attachments/assets/115bb0dc-dc45-4d00-842e-584101df0c3e)

l. Generate first 'n' program numbers

![l](https://github.com/user-attachments/assets/cfebda16-486b-4b2b-a225-0a3309675371)

**NO.3 WAP to create a pyramid of the character '*' and a reverse**

![pyramid](https://github.com/user-attachments/assets/a77ed0f8-b205-44b0-a543-cae5236c054d)

**NO.8 WAP that accepts a character and performs the following:**

a.) print whether the character is a letter or numeric digit or a special character https://www.programiz.com/online-compiler/8JecBnWaL7Ge1

![8](https://github.com/user-attachments/assets/0f702921-d3da-4722-acb6-5d90d84bf179)

b.) if the character is a letter, print whether the letter is uppercase or lowercase

![b](https://github.com/user-attachments/assets/dc2e684a-c9c9-4a59-b4f2-3434143d4054)

c.) if the character is a numeric digit, print its name in text (eg. if input is 9, output is NINE)

![C](https://github.com/user-attachments/assets/0ab3aa3e-a752-4df1-a2fa-815120ebf3e4)

**NO.9 WAP to perform the following operations on a string** 
https://www.programiz.com/online-compiler/53aZNy9W4JtBO

a.) Find the frequency of a character in a string
b.) Replace a character by another character in a string 
c.) Remove the first occurence of a character from a string
d.) Remove all occurence of a character from a sting 
![9](https://github.com/user-attachments/assets/04b3e1ae-fba9-41a0-8e01-7bb826e8c42b)

**NO. 10 WAP to swap the first n characters of two strings**
https://www.programiz.com/online-compiler/8Tj0VB0YQWuIe

![10](https://github.com/user-attachments/assets/7ad8cc5a-4ff0-4487-b782-ae8d679e8ce2)

**NO.11 Write the function that accepts two strings and returns the indices of all occurences of the second string in the first string as a list. If the second string is not present in the first string then it should return-1.**

https://www.programiz.com/online-compiler/9I9jfio3jb31R

![11](https://github.com/user-attachments/assets/3090aad1-079c-4791-bfe1-9c3e0f4b9c0d)

 **NO.12 WAP to create a list of the cubes of only the even integers appearing in the input list (may have elements of other types also) using the following:**
  a.) 'for' loop 
  b.) list comprehension    https://www.programiz.com/online-compiler/4apzwMD2Ae7Ww

  ![12](https://github.com/user-attachments/assets/76920724-c6b3-41dd-b768-bcc79a97f622)


**NO.13 WAP to read a file and**   
**m.) Print the total number of characters, words and lines in the file.**

 ```bash
   python file_operations.py

filename=input("Enter filename:")
file=open(filename, 'r') 
lines = file.readlines()
num_lines = len(lines)
num_words = sum(len(line.split()) for line in lines)
num_chars = sum(len(line) for line in lines)
print(num_chars, num_words, num_lines)
        '''
  

**n.) Calculate the frequency of each character in the file. Use a variable of dictionary type to maintain the count.**

 ```bash
   python file_operations.py

def character_frequency_in_file(filename):
    freq = {}
    with open(filename, 'r') as file:
        text = file.read()
        for char in text:
            freq[char] = freq.get(char, 0) + 1
    print(freq)

character_frequency_in_file("sample.txt")
     '''



**o.) Print the words in reverse order**

 ```bash
   python file_operations.py

def reverse_words_in_file(filename):
    with open(filename, 'r') as file:
        words = file.read().split()
    print(' '.join(reversed(words)))

reverse_words_in_file("sample.txt")
   '''

          


  
































