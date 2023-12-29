# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific location of interest
### Step 2: 
In the same location as the text file, create a python program
### Step 3: 
In python program, import sys and open a text file with argument 'sys.argv[1]'
### Step 4:  
Using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
Using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
#Program to get hte word count using command line arguments
#Developed by: Joel John Jobinse
#Register Number: 212223240062
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        words=line.split()
        count+=len(words)
print("no of words",count)
```
### OUTPUT:
![py5b](https://github.com/joeljohnjobinse/command-line-arguments-to-count-word/assets/138955488/8ba24656-3529-4604-b322-21a0fe56ec41)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
