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
counter = counter + 1; #add any number to counter
counter += 1; #add any number to counter 
counter++; #only adds plus 1 to counter
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
else if (x == y)# not needed because if other 2 are false than x == y is true
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
