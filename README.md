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
#developed by: ROSHINI S
#register number : 212223240142

with open("hello.txt",'r') as file1:
    msg=file1.read()
with open("program.txt",'w') as file2:
    file2.write(msg)
```
### OUTPUT:

![Screenshot 2024-05-11 182907](https://github.com/Roshini2201/Copy-File/assets/154105318/78bc57ec-2933-4f2c-b1d2-1f225520d67d)

![Screenshot 2024-05-11 183732](https://github.com/Roshini2201/Copy-File/assets/154105318/906d9135-4f18-4b88-b504-69325814e0f6)

![Screenshot 2024-05-11 182943](https://github.com/Roshini2201/Copy-File/assets/154105318/d306149e-481b-4818-8650-770ab250ba4b)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
