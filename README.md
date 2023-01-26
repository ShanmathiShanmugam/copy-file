# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

### Step 2: Using keyword "with" to open the requied file.
 
### Step 3: Again using the with keyword to open the empty file.

### Step 4: The empty file is open by using 'W' which is used to write only.

### Step 5: The four function is used to take each line from the main file.

### Step 6: The four function is used to take each line from the main file.

### Step 5: Print the output.

## PROGRAM:
```python
developde by: S.Shanmathi
registered number: 22003171
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)
```

### OUTPUT:
![image](https://user-images.githubusercontent.com/121243595/214904641-0ca88cff-f2b1-41d8-8428-26b37e5e73ea.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
