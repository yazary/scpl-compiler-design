# SCPL (Simplified C Programming Language) - Language Specification

## Introduction
SCPL is a simplified version of C Programming language, which has almost all the imporatant consrtucts of C Programming. This language specification has been defined for the Compiler design project. The specifications given here are not the final ones. I may be adding / editing / removing varous constructs / syntax during as I do the project.

## Main function.
Executions of a SCPL starts with main function. The way to define it is.

```C
main (){
  <statements>;
}

```

* Every SCPL statemnts should end with a semi colon.
* { } - Are used to block together statements and it is mandatory for main, and other control structures(like if, loops et.), even if just one statement is present in the control structure.
* SCPL is case sensitive.

## Data Types
SCPL supports the following basic data types:
* int - Used for integers(Stored as 32 bit signed integer internally).
* float* - Used to store floating point number. Used IEEE-754 floating point representation to store it internally.
* char - Used to store Characters, in 1 byte ASCII code representation. Characters are represented in single quotes. Eg: 'a', 'b' etc.
* bool - Used to store boolean data type. It can take either of the values true / false.

## Identifiers / Variables.
* Variable name should start with an alphabet / uderscore( _ ) and can be followed by any combination of characters, digits and underscore ( _ ).
* All variables should be declared before the actual use.
* Initialization of the values are also possible for variable.

Syntax for variable declaration:
```C
  <data_type>  <vriable-1> [,< variable-2>, <variable-3>....];
  <data_type> <variable-1> = expr1 , [<variable-2>...];
```

Eg:
```C
  int x = 100;
  char ch = 'a', ch2;
```
## Operators
### Arithmetic Operators
### Boolean Operators
### Logical Operators


## Control Structures
## Selectors
### if
Syntax:
```C
  if(<condition>){
    statements...
  }
```

Eg:
```C
  if(x > 100){
    x = x + 100;
  }
```

### if-else
```C
  if(<condition>){
    statements...
  } else {
    statements...
  }
```

Eg:
```C
  if(x > 100){
    x = x + 100;
  } else {
    x = x + 200;
  }
```
### if-else if-else

### goto statements

## Loops
### For Loop

### While Loop

### Do-While Loop

## Functions

## Input-output functions

## Structures *


\* : Constructs which will be added later on, only after the main constructs are added.


