# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys


### Step 2: 
Open file using commandline arguments.
 
### Step 3:
Using for loop find the word count from the contents of a file.


### Step 4:  
Use len to count number of words.

### Step 5:
Give print statement.


### Step 6: 
End the program.


## PROGRAM:
```python
#Developed by:yuvabharathib
#Registration no:22002787
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word = line.split()
        count+= len(word)
print("World Count in File = ",count)   
```

### OUTPUT:
![Screenshot from 2022-10-06 14-14-03](https://user-images.githubusercontent.com/113497404/194267142-be01defd-8c28-4bcf-842c-6ddb2d8b67f1.png)
![Screenshot from 2022-10-06 14-19-08](https://user-images.githubusercontent.com/113497404/194267235-f48b6ca8-a08d-4ed4-8ccc-9a4f83c8ad2d.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
