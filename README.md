# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.

### Step 2: 
Print the number of contents to be displayed using df.head().
 
### Step 3: 
The number of rows returned is defined in Pandas option settings.

### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5: 
Increase the maximum number of rows to display the entire DataFrame

### Step 6: 
End the program.

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
