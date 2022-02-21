# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import the sys module.

Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1].

Step 3:
Read the file using read() method.

Step 4:
Use split() method to split the file content into words.

Step 5:
Use len() to find the total words.

Step 6:
Run the program to determine the number of words in the file created

## PROGRAM:
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("Word Count in File = ",count)
### OUTPUT:
![Screenshot (64)](https://user-images.githubusercontent.com/94828604/154996252-fbf369d1-f7d2-4591-8496-bd8aff4d9f4d.png)
![Screenshot (66)](https://user-images.githubusercontent.com/94828604/154996731-48c9f853-f594-467c-a6e3-43ad3693ad0e.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
