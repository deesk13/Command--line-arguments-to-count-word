# Command--line-arguments-to-count-word
## NAME: DEVA DHARSHINI I

## REGISTER NO: 212223240026
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 Open the file and assign it to f1
### Step 3: 
Read the file and assign it to data
### Step 4:  
Split the data (data.split())
### Step 5: 
Print the assigned variable's length using len(word)
### Step 6: 
End the program
## PROGRAM:
```
Developed by:  DEVA DHARSHINI I
Register no: 212223240026
import sys
count=0
with open(sys.argv[1],'r') as f1:
     for i in fp:
        words=i.split()
        count+=len(words)
print("word count  in file is",count)
```
### OUTPUT:
![Screenshot 2024-05-12 141419](https://github.com/deesk13/Command--line-arguments-to-count-word/assets/150927063/46b78b4c-ad70-472d-85bd-e9e50551dfc2)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
