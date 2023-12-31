# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the Source File for Reading:

Use the open function with the 'r' mode to open the source file ('file.txt') for reading. Assign the file object to the variable source.
### Step 2: 
Read Content from Source File:

Use the read method on the source file object to read the content of the source file. Assign the content to the variable content.
### Step 3: 
Open the Destination File for Writing:

Use the open function with the 'w' mode to open the destination file ('.txt') for writing. Assign the file object to the variable destination.
### Step 4:  
Write Content to Destination File:

Use the write method on the destination file object to write the content to the destination file.
### Step 5: 
After executing the code, the file content of 1 will be copied to file 2

## PROGRAM:
```
# Program for copying the contents from one file to another file.
# Developed by : K Madhava Reddy
# RegisterNumber : 212223240064

with open("file.txt","r") as f1:
    with open("Myfile.txt","w") as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![image](https://github.com/Madhavareddy09/copy-file/assets/145742470/14a08a17-de60-493f-abaf-dd40a23e6e44)
<br>
![image](https://github.com/Madhavareddy09/copy-file/assets/145742470/c1b19ccd-7174-4b3f-bfb4-ca56cf1c680e)
<br>
![image](https://github.com/Madhavareddy09/copy-file/assets/145742470/2679eb2c-a0d1-4889-bfdb-4fe613217afb)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
