# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some content in it.

### Step 2:
Open the created text file.

### Step 3:
Create another empty text file.

### Step 4:
Copy the content of text file to empty file using write function.

## PROGRAM:
```
#Program for copying the contents from one file to another file
#Developed by: KAMALESH R
#RegisterNumber: 212223230094
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![image](https://github.com/KAMALESHNITHYA/Copy-File/assets/145743119/cb1e8af3-f813-4924-a734-0f7d90a1a35f)
![image](https://github.com/KAMALESHNITHYA/Copy-File/assets/145743119/31dcb7bc-5e6c-4fc6-9c10-8d89389aa781)
![image](https://github.com/KAMALESHNITHYA/Copy-File/assets/145743119/98ed2ec4-f75c-4e24-ba79-25e5b71a6bb0)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
