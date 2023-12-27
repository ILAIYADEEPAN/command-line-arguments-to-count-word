# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import the sys module.
### Step 2: 
 pass the file name as the first argument after the name of the script open the file as sys.argv[1]
### Step 3: 
 read the file using read() method.
### Step 4:  
use split() method to split the file content into words
### Step 5: 
 use len() to find the total words.
### Step 6: 
run the program to determine the number of words in the file created.
## PROGRAM:
```
import sys
fp = open(sys.argv[1])
data = fp.read()
words=data.split()
print("Total words:",len(words))
```

### OUTPUT:
![292854737-cc322f0f-3a00-4cda-bdc0-a393446243d0](https://github.com/ILAIYADEEPAN/command-line-arguments-to-count-word/assets/147473334/4d311e7b-f7fa-4003-b70e-f3c96eb1061c)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
