# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words is 0
### Step 2: 
Open it with txt file
### Step 3: 
Give range for i
### Step 4:  
Then next split the words
### Step 5: 
Count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```python
#Program for getting the word count from a text
#Developed by: ROGITH. K
#Reg num: 212223110042
num_words=0
with open('trty','r')as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
## Text file:
![alt text](<Screenshot 2024-05-12 142414.png>)
## Program output:
![alt text](<Screenshot 2024-05-12 142449.png>)
## RESULT:
Thus the program is written to find the word count from a text.
