# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2: 
 Create a file pointer and open the file.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
### step 7:
Close the file pointer and end the program.
## PROGRAM:
y or specify it wit```
Developed by: Kishore .N
Register no: 212223230106
```
```py
def wordcount(filename):
    fp=open(filename)
    wordcount=0
    for i in fp:
        words=i.split()
        wordcount+=len(words)
    print("Total no of words in file is",wordcount)
    fp.close()
wordcount(input("Enter a filename in current directorh full path:"))
```
### OUTPUT:

![image](https://github.com/kishorenagarajan08/Word-Count/assets/155753188/26f0b5f7-ab81-4e9b-a77d-03d136b88aa6)


## RESULT:
Thus the program is written to find the word count from a text.
