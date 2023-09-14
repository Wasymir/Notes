# Program Translation

14.09.2023

___

## Interpreter & Compiler

They both translate human-readable programming language into machine code

### Compiler translates the entire code at once
```
+---+           +---+
|~~~|           |110|
|~~~|   +---+   |001|
|~~~|-->| C |-->|101|
|~~~|   +---+   |111|
|~~~|           |010|
+---+           +---+
```

### Interpreter translates code line by line

```
   +---+   +---+   +---+
1. |~~~|-->| I |-->|101|
   +---+   +---+   +---+

   +---+   +---+   +---+
2. |~~~|-->| I |-->|101|
   +---+   +---+   +---+

   +---+   +---+   +---+
3. |~~~|-->| I |-->|101|
   +---+   +---+   +---+
```
### Compiler
1) initial compilation takes some time, after compilation runs quickly.
2) has a global view of the code, so can detect problems in any part when compiling, especially syntax errors.
3) results in an executable file, which can be run without the compiler.
4) need to wait for the whole compilation process, even for minor changes

### Interpreter
1) only needs to store & operate on one line, so less memory demand.
2) we can detect errors only in the lines of code that are actually run when we execute the program.
3) need interpreter to run the program every time.
4) faster feedback
5) has access to information about which parts of the code are the most important i.e. executed most often.


## Compilation Process
1) Source code\
**Lexical Analysis**
2) Tokenized code i.e. code divided into keywords, variables names, numbers\
**Syntactic Analysis (aka Parsing)**
3) Code with correct syntax & classified constructions (aka AST)\
**Semantic Analysis**
4) Code with fewer semantic errors\
  **Intermediate code generation**
1) Intermediate code\
**Intermediate code optimization**
2) Optimized intermediate code\
**Machine Code Generation**
1) Machine Code


