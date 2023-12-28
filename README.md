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
![Screenshot 2023-12-28 130035](https://github.com/Thilakeshwaran/command-line-arguments-to-count-word/assets/147473132/8234c78d-bf6b-42c2-a8a7-3872fcf642a4)
![Screenshot 2023-12-28 130054](https://github.com/Thilakeshwaran/command-line-arguments-to-count-word/assets/147473132/4fe48f1d-5c5e-4345-b345-5fbed6aedc6b)
![Screenshot 2023-12-28 130126](https://github.com/Thilakeshwaran/command-line-arguments-to-count-word/assets/147473132/52d413ff-45ec-4033-8b5d-5be0f102b980)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
