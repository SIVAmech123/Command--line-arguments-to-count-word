# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Import sys module to use command line arguments.

# Step 2:
Create a file pointer and open the file which is passed in command line.

# Step 3:
Initialize word count as zero.

# Step 4:
For each line in file, split it into words and find number of the words in every line.

# Step 5:
Sum the number of words in each line.

# Step 6:
Display the total words in the file.

## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: sivakumar.R
# Register number: 212223230209
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![Screenshot 2024-05-10 183946](https://github.com/SIVAmech123/Command--line-arguments-to-count-word/assets/151629067/766b7159-767a-423d-aa42-a0d398171114)


![Screenshot 2024-05-10 183953](https://github.com/SIVAmech123/Command--line-arguments-to-count-word/assets/151629067/91f34be3-f61c-46fb-94b5-9a7151aa9a61)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
