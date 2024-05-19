# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create a text file with some content in it.

Step 2:
Open the created text file.

Step 3:
Create another empty text file.

Step 4:
Copy the content of text file to empty file using write function.
## PROGRAM:
with open("nakul.txt",'r') as file1:
    msg=file1.read()
with open("nakulnew.txt",'w') as file2:
    file2.write(msg)
### OUTPUT:
![Screenshot 2024-05-19 132151](https://github.com/Nakul1411/Copy-File/assets/138849780/eb8eb03e-d5f1-466f-b9f3-5796a47cddcc)
![Screenshot 2024-05-19 132208](https://github.com/Nakul1411/Copy-File/assets/138849780/777af908-aaf2-4dda-bfa0-de3ca68abd10)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
