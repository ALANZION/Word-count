# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
### Step 1:
Open the file in read mode and handle it in test mood.
#### Step 2:
Read the text using read() function.
### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space
character.
### Step 4:
The length of the split list should equal the numbers of words in the test file.
### Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after
splitting.
### Step 6:
End the program. 


## PROGRAM:
```
def program():
count=0
with open("john.txt","r") as f:
for data in f:
words=data.split()
for word in words:
count+=1
print("Ttotal number of words:",count)
program()

```

### OUTPUT:

![Screenshot 2023-12-29 221246](https://github.com/ALANZION/Word-count/assets/145743064/5bedec97-75c5-47c4-9d57-e4609168a7da)


## RESULT:
Thus the program is written to find the word count from a text.
