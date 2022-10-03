# cLox
A C implemetation of the bytecode virtual machine Lox compiler from the book "Crafting Interpreter" (http://www.craftinginterpreters.com/)

## Code Organization

The code is organized so that each chapter is on its own branch. At the end of each chapter, the branch will be merged into `main`. Any coded challenges will be commited to the chapter branch and will not be merged into `main`.

```text
^ * xxxxxxx (chapter-14) Challenge 14.2 Implementation of `writeConstant` function
| * xxxxxxx Challenge 14.2 `writeConstant` function
|/
*   xxxxxxx (main) Chapter 14
|\  
| * xxxxxxx 14.6 Line Information
| * xxxxxxx 14.5 Constants
| * xxxxxxx 14.4 Disassembling Chunks
| * xxxxxxx 14.3 Chunks of Instructions
| * xxxxxxx 14.2 Getting Started
|/  
* xxxxxxx Initial commit
```
