# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a file with .txt file extension
### Step 2: 
 add some text in that file
### Step 3: 
create a python file
### Step 4:  
write a code to count the number of words in that file
### Step 5: 
run the program
### Step 6: 
display the output
## PROGRAM:
```
# DEVELOPED BY : THILAKESHWARAN
# REFERANCE NUMBER :23013560
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Ttotal number of words:",count)
program()
```
### OUTPUT:
![OUTPUT](/Screenshot%202023-12-28%20130035.png)
![OUTPUT](/Screenshot%202023-12-28%20130054.png)
![OUTPUT](/Screenshot%202023-12-28%20130126.png)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
