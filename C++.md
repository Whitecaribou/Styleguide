# C++

## Declarations
### Variables
Valiable declatarions must be arranged top-to-bottom in alpha/complex order starting with the type and then the name.

This means that `chars` are declared before `ints` and `std` instances are declared after `ints`.

Pointers are always declared at the end of a type block.

```C++
char name[4] = "Tom";
char *input;

int status = 1;
int *pointer;
int *pointerTwo;

std::string message;
```

## Braces
The opening brace must always be on the same line as the control structure seperated from the ending parenthesis by a single non-breaking space.

The ending brace must either be on its own line signalling the end of the block or, in the case of `else`, `catch`, ect., it is on the same line as the next control structure seperated from it by a single non-breaking space.

```C++
if (nullPointer !== null) {
    // Code
} else {
    // Code
}
```
