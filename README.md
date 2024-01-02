# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open vizual studio code.
### Step 2: 
Create file with .py extension. 
### Step 3: 
Start the program.
### Step 4:  
Write the code.
### Step 5: 
Run terminal for output of the given program.
### Step 6: 
End the program.
## PROGRAM:
```
'''
#Program to find the word count
#Developed by:NISHA.D
#Register number:212223230143
'''
num=0
with open("cartoon.txt","r")as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![Alt text](<Screenshot 2024-01-02 141735.png>)


## RESULT:
Thus the program is written to find the word count from a text.
