

---
# Computationl Biomechanics

Using Matlab for Scintific Computing and Research in Biomechanics

---

# Why do we need to use Matlab?

---


 Scientific computing is the science of solving problems with computers. The problems themselves usually arise from other disciplines such as mathematics, engineering, biology, physics, chemistry and -Biomechanics- As a consequence, scientific computing and Matlab is inter-disciplinary by nature.
 <cite>Me</cite>

---



### Scaler Arithmetic Operations

Scalars are mathematical entities which have only a <br>
magnitude­ (and no direction). Physical examples may <br>
include mass and energy. 

---
### Scaler Arithmetic Operations

Here's are a few scalar operations that we can use:

<center>


| Symbol 	| Operation      	| In Matlab 	|
|:--------:	|----------------	|-----------:	|
| ^      	| exponentiation 	| a^b       	|
| *      	| multiplication 	| a*b       	|
| /      	| division       	| a/b       	|
| +      	| addition       	| a+b       	|
| -      	| substraction   	| a-b       	|

</center>

---

>Commands and Expressions 
<center>

- MATLAB retains your previous keystrokes. <br>
- Use the up-arrow key to scroll back back through the commands.<br>
- Press the key once to see the previous entry, and so on.<br>
- Use the down-arrow key to scroll forward. Edit a line using <br>the left- and right-arrow keys the Backspace key, and the Delete key.
- Press the Enter key to execute the command.<br>

</center>

---

### The Order of Execution of Operations

<center>

| Order     | Operations                                                                            |
|:-----:    | ------------------------------------------------------------------------------------: |
| First     | Parentheses                           |
| Second    | Exponentiation                                         |
| Third	    | Multiplication and division |
| Fourth	| Addition and subtraction                              |


</center>

---

#### A few Examples 

```Matlab

>> 8 + 3*5
ans =
     23
>> 8 + (3*5)
ans =
     23
>>(8 + 3)*5
ans =
     55
>>4^2­12­ 8/4*2
ans =
     0
>>4^2­12­ 8/(4*2)
ans =
     3


```

---

#### Managing the work session

Matlab provices us with basic commands to manage work sessions. <br>
Here are a few of them.

<center>

<center>

|Commands| What it does |
|:----:|:------------------------------:|
|clc|	Clears the Command window.|
|clear|	Removes all variables from memory.|
|clear v1 v2| 	Removes the variables v1 and v2 from memory.|
|quit|	Stops MATLAB.|

</center>

</center>




#### Vector variables (Arrays)



---
##### How to make an Array

    - Colon creates a sequence of numbers in a row
    - Comma, separates listed elements of a single row, can also use an empty space
    - Semicolon, separates the rows

for exampple,

```
>> p = [1,7,3;4:6;7 8 9]
p =
     1     7     3
     4     5     6
     7     8     9

```

---


##### Functions built-in Arrays
    - We can find the size of an array with the size() function
    - We can also find the length of a vector with the length() function
for example

```
>>p = [5:5:35;35:-5:5];
>>size(p)
ans =
    2	7
>>r = [4,5 6];
>>length(r)
ans =
	3

```

---

##### Concatenation of Arrays

```
>> p = ones(3,1)
p =
     1
     1
     1
>> q = zeros(3,1)
q =
     0
     0
     0


>> s = [p q q p]
s =
     1     0     0     1
     1     0     0     1
     1     0     0     1

```