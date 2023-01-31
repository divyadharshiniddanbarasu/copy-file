# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
##### Step 1:Create a file.

##### Step 2:Write some lines in that file.

##### Step 3:Create a python file.

##### Step 4:Write a code to copy the content of the file to a new file.

##### Step 5:Run the program.

##### Step 6:Display the output.

## PROGRAM:
```
with open("text.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/119393424/215855826-ff898d21-a3bd-4138-9984-f74923e72170.png)
![image](https://user-images.githubusercontent.com/119393424/215855870-7a9702dc-875a-46e6-8ee3-9c2eb970b73c.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
