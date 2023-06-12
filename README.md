# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.

##Step 2:
On the same location as the text file, create a python program file.

##Step 3:
In python Program, import sys and open a text file with argument "sys.argv[1]"

##Step 4:
using read() and split(), split the lines in the file into a sequence of words.

## Step 5:
using len() count the number of words in the text file.

##Step 6:
In command prompt, initiate python followed by program name and text file name to get the outpu

## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: Naveen Raja N.R
RegisterNumber:212222230093
'''
import sys
count=0
fp=open(sys.argv[1],'r')
for line in fp:
    list1=line.split()
    count+=len(list1)
print("no of words in a file",count)
```
## OUTPUT:
![image](https://github.com/naveenraja2004/command-line-arguments-to-count-word/assets/118707204/b46341bd-ab25-4c3b-821d-f685abfa4621)

![image](https://github.com/naveenraja2004/command-line-arguments-to-count-word/assets/118707204/30816ac3-198b-403a-863d-8e0b81423ebb)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
