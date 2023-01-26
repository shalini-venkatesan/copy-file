# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode
### Step 2: 
Open the second file in append mode
### Step 3: 
Every word in first file is copied to second file using write()
### Step 4:  
close the first file
### Step 5: 
close the second file

## PROGRAM:
```py
## Python program for copying the contents from one file to another file.
##Developed by: Shalini V
##Register no: 22009257
with open('f1.txt','r') as file:
    with open('cft.txt','a') as file2:
        for i in file:
            a=file2.write(i)
file.close()
file2.close()       
```
### Sample input:
![output](/file1.png)
![output](/lala.png)
### OUTPUT:
![output](/cft.png)
## RESULT:
Thus the program is written to copy the contents from one file to another file.