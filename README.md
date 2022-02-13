# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:First we need to open the required file from which we need to copy the test.

### Step 2:Using keyword "with" to open the required file. 
 
### Step 3:Again using the width keyword to open the empty file.

### Step 4: The empty file is open by using "w" which is used to write only 

### Step 5: The for function is used to take each line from the main file.

### Step 6: Write() is used to write the linesof main file to the empty  file or do the directed file.

## PROGRAM:
with open("file1.txt","r") as fp:
        V = fp.read()
        print(V)

### OUTPUT:
![output](./C1.PNG)

![output](./C2.PNG)

![output](./C3.PNG)




## RESULT:
Thus the program is written to copy the contents from one file to another file.