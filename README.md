# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
 Read the file and store in a variable.

### Step 3: 
Now create a new file in which we want to paste the content using write access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```
#python program for copying a file
#Developed by: Sudharsana Kumar S R
#Ref.no: 23007374
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)  
```
### FILE:
![python 5c 1](https://github.com/sudharsanakumar18/copy-file/assets/138849110/71aad897-a31b-4a52-ad2c-8a09f4335703)

### OUTPUT:
![python 5c 2](https://github.com/sudharsanakumar18/copy-file/assets/138849110/ce8ae4f5-43f2-4cbe-90eb-21803e654e84)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
