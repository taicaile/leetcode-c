# Function Pointer

```c
#include <stdio.h>

void foo(int x){
    printf("the input is %d\n", x);
}

int main(int argc, char const *argv[])
{
    void (*bar)(int x) = foo;
    /*
    void, the function return type
    (*) function pointer type
    bar function pointer name
    (int x) parameters
    */
    bar(12);
    return 0;
}
```
