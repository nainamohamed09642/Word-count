# Word-count
## AIM:To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 

##Step 1:
To write a python program for getting the word count from a text file

##Step 2:
Open the required file by using the function "with".

##Step 3:
Then use the laptop to assign the i value in the file.

##Step 4:
Using split function to spilt the words

##Step 5:
Finding the given length of the words by using len() fuction.

###Step 6:
Calling the function and Printing the number of words 

## PROGRAM:
```
#Program to find the word count.
#Developed by: DHANUSH P 
#RegisterNumber:23001835
num_word=0
with open ("sample.txt",'r') as f:
for i in f:
word=i.split()
num_word+=len(word)
print("number of words ={}".format(num_word)
```

### OUTPUT:
![292836852-fb57c189-e309-4dd3-bd90-a1c1e044808b](https://github.com/nainamohamed09642/Word-count/assets/151916360/96acf1b6-b961-4daa-86de-bd519b3db32c)
![292836885-1a2ca477-6077-4638-a0ca-e147ce0806bd](https://github.com/nainamohamed09642/Word-count/assets/151916360/902873d8-c28f-4b90-b451-6fa41d63477a)

##Result:
Thus the program is written to find the word count from a text.



## RESULT:
Thus the program is written to find the word count from a text.
