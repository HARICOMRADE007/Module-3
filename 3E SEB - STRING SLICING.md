# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.No: 212222060074
#Name: Hariharan K
#Add Your Code Here
def splitstring(a):
    x = a.split('@')
    print(x)

```

### OUTPUT
<img width="928" height="242" alt="image" src="https://github.com/user-attachments/assets/aad8455b-9d3a-4588-bc27-4a33280296ab" />


### RESULT
Thus the program that splits an email ID string into two parts using the "@" symbol has been implemented and executed successfully.
