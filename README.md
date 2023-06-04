# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it

### Step 2: 
Open the text1.txt file in read mode

### Step 3: 
Create a copy.txt file using write mode

### Step 4: 
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: S.ROSELIN MARY JOVITA
RegisterNumber: 212222230122
'''
with open("text2.txt", 'r')as fp:
    msg1=fp.read()
with open("copytxt",'w')as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![copytext1](https://github.com/Roselinjovita/copy-file/assets/119104296/50abdc12-05f5-46e2-ba5e-7219a795bd34)


![copytext2](https://github.com/Roselinjovita/copy-file/assets/119104296/977fc304-e1cc-42d8-8f0d-d206ef5cc306)

![copytext3](https://github.com/Roselinjovita/copy-file/assets/119104296/33a00d39-0fa6-46d0-8c45-2d3842035c03)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
