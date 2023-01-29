# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

### Step 2: 
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4: 
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

### Step 6: 
The four function is used to take each line from the main file.

### Step 5: 
Print the output.

## PROGRAM:
```python
#developde by: S.Shanmathi
#register number: 22003171
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
    for line in firstfile:
             secondfile.write(line)
```

### OUTPUT:
![5c-1](https://user-images.githubusercontent.com/121243595/215338458-a92a3762-5149-437a-ab3a-9f384cbd6165.jpg)
![5c2](https://user-images.githubusercontent.com/121243595/215338466-675af177-fecf-4b12-aa6e-c234be80bd78.jpg)
![5c3](https://user-images.githubusercontent.com/121243595/215338470-ef77a197-ca82-4608-bc95-669c5ea40d1e.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
