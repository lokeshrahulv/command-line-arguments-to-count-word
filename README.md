# Command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys
### Step 2: 
 Initially make count = 0
### Step 3: 
Open the content file using command line arguments.
### Step 4:  
By using for loop name the function as "line"
### Step 5: 
Split the line using .split
### Step 6: 
Count the length of the word and print it
## PROGRAM:
```
Developed by LOKESH RAHUL V V
Register no: 22004702

import sys
count=0
with open(sys.argv[1],'r') as file:
        for line in file:
            word=line.split()
            count += len(word)
print("Program is developed BY: LOKESH RAHUL V V")            
print("Word count in file= ",count)
```
### OUTPUT:

![file1](https://user-images.githubusercontent.com/118423842/214762622-c1ad77e9-e27f-4643-99b4-13be9fbd308b.jpg)

![file2](https://user-images.githubusercontent.com/118423842/214762643-aa268167-e450-48d6-9c42-8b31d5e97251.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
