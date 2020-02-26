# Notes in C language


Scartch  say(hello, world)
```C <- Tells Markdown code is "C"
printf("hello, world\n");
```

All printed words are called strings and strings are enclosed by "string"<br>
\n tells computer to start a newline<br>
; is like the period at the end of a sentence. It tells the computer that this is the end of the statement.<br>

Scratch: set counter to 0
```C
int counter = 0;
```

In C, you must declare the type of varianle you are creating

Scratch: change counter by 1
```C
counter = counter + 1; //add any number to counter
counter += 1; //add any number to counter 
counter++; //only adds plus 1 to counter
```

Scratch: if x is less than y say x is less than y
```C
if (x < y)
{
printf("x is less than y\n");
}
```

Scratch:if x is less than y say x is less than y else say x is not less than y
```C
if (x < y)
{
printf("x is less than y\n");
}
else
{
printf("x is not less than y\n");
}
```

Scratch: if x is less than y say x is less than y else if x > y say x is greater than y else if x = y say x is equal to y 
```C
if (x < y)
{
printf("x is less than y\n");
}
else if (x > y)
{
printf("x is greater than y\n");
}
else if (x == y) // not needed because if other 2 are false than x == y is true
{
printf("x is equal to y");
}
```

Scratch: forever say hello, world
```C
while(true)
{
printf("hello, world\n"); 
}
```

Scratch: repeat say hello, world 50 times
```C
for(int i = 0; i < 50; i++)
{
printf("hello, world\n"); 
}
```

Scratch: ask What's your name? say answer
```C
string answer get_string("What's your name?\n");
printf("%s", answer);
```

Scratch:ask What's your name? say hello, answer
```C
string answer get_string("What's your name?\n");
printf("hello, %s", answer);
```

Scratch:
```C

```

```C
#include <stdio.h>

int main(void)
{
printf("hello, world\n");
}
```
Source Code -> Compiler -> Machine Code
run a file: ./filename.extension
convert to machine code: clang filename.extension
convert to machine code with name: clang -o wantedname filename.extension
convert to machine code: make filename
%i sub in int
%s sub in string
Number with decimal -> float
%f sub in float

Finite memory storing infinite numbers/precision- not possible

Copy/Paste = Bad


Do-While Loops ensure the loop ccommand is executed at least 1 time
## Lecture 2

**Source code to Machine code steps (Compiling):**
* Preprocessing:
    * #include lines happens before compiling, header files
* Compling: convert source code to Assembly code
* Assembling: turns assembly code into binary 0's and 1's
* Linking: places individual binary files one after another (combines/links) so it is one "string" of 0's and 1's 


* use printf() for diagnostic purposes
* whenever code does not give intended results

Array: contiguous "chunk" of memory for string information

return if you need to use something from the function

"Global" variable- written in all caps, 

heap: variables use this, "top" of memory

stack - Functions use this, "bottom" of memory<br>
<br>
<br>
<br>
Hash Table: Relates "keys" to "values" and "keys" do not need to be ints


Linked List: Arrays that are NOT stored contiguously

Dictionary: 
