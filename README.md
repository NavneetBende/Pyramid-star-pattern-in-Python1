Pyramid star pattern
To print the Pyramid star pattern we need two loop. first is outer loop and second is inner loop.

first loop that is the outer loop works on the row or line and the another loop that is inner loop works on the column mean how many start you want to put in the single line.so here we need to now proper working of the loop that we can easily make a desired pattern.

Now we will discuss all possible star pattern using java. 


1. Write a Program to print the following pattern.
* 
* * 
* * * 
* * * * 
* * * * *
Working
Step 1- first you need to initialize two variable for loop.

Step 2- the first loop  for the row.

Step 3-  the second loop work for the column.

Step 4- now print the *.

Step 5- now out side of loop, put new line.

Step 5- stop.

C	JAVA	Python 1	Python 2	C++
for i in range(5):
    for j in range(i+1):
        print(“*”,end=” “)
    print()
2. Write a program to print the following pattern
* 
* * * 
* * * * * 
* * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
for i in range(5):
    for j in range(2*i+1):
        print(“*”,end=” “)
    print()
3. Write a program to print the following pattern
        * 
      * * 
    * * * 
  * * * * 
* * * * *
C	JAVA	Python 1	Python 2	C++
n=5
for i in range(n):
    for j in range(n): 
        if(i+j<n-1):
            print(” “,end=“”)
        else:
            print(“*”,end=“”)
    print()
4. Write the code to print the following patter
                * 
            * * * 
        * * * * * 
    * * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
n=5
for i in range(5):
    for j in range(2*n+1):
        if(j<(2*n-1)-(2*i-1)):  
            print(” “,end=“”)
        else:
            print(“*”,end=“”)
    print()
5. Write the code to print the following pattern.
    *
   ***
  *****
 *******
*********
C	JAVA	Python 1	Python 2	C++
n=5  
for i in range(5):
    for j in range(2*n+1):
        if(j<n-i-1):       
            print(” “,end=“”)
        else:
            print(“*”*(2*i+1),end=“”)
            break
    print()
