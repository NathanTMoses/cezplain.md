# How do you start a C file?
## The basics
The basic way to start a C file is the following : 
```
#include <...>

int main(...)
{

}
```
Let me explain...
## The source files
C is really hard if you don't have function pre-built into your program. And that's exactly what source files are.
The most common one is `stdio.h` so we'll add that in.
Also if you are beginning CS50, you also might want to add in `cs50.h`
### Now I'm going to add void in the parantheses because this is for beginners. I have a another section on argv and argc coming up soon.
Now we have : 
```
#include <stdio.h>
#include <cs50.h>

int main(void)
{

}
```
## Finishing up
And that's it!
You put code inside the `{ }` (Also known as brackets).
