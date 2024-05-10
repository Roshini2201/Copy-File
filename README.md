# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function as copy with arguments existing file, new file name.
### Step 2:
Open a function to read.
### Step 3:
Open a function to write
### Step 4:
Copy the contents from existing file to the new file.
### Step 5:
End the program

## PROGRAM:
```
#DEVELOPED BY: ROSHINI S
3REDISTER NUMBER : 212223240142

with open ("sys.txt",'r')as fp:
  msg = fp.read()
with open("copytxt",'w') as fp1:
  fp1.write(msg)
```
### OUTPUT:

![WhatsApp Image 2024-05-10 at 20 04 32_3f97112a](https://github.com/Roshini2201/Copy-File/assets/154105318/9b80ca25-5619-47c8-9585-631a8200958a)

![WhatsApp Image 2024-05-10 at 20 04 57_6c154077](https://github.com/Roshini2201/Copy-File/assets/154105318/4c58d256-5c20-4488-8f6c-bfb111c2a659)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
