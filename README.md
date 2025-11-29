# bytecraft

# Bytecraft Language Documentation (v1.0)

Bytecraft is a beginner-friendly programming language designed to teach programming concepts.

## 1. Installing Bytecraft

After running the installer:

Bytecraft is installed to C:\Program Files\Bytecraft (default)

bytecraft.exe is added to your PATH

Open a terminal and run programs:

## 2. File Format
Bytecraft programs are plain text files with .bc extension.

Comments start with // and are ignored.

Each command is written on a separate line.

## 3. Variables
Variables are declared using assign:

## 4. Printing Output
Use say() to print values:

## 5. Comments
Start with //

Can be placed anywhere on a line:

## 6. Errors
Bytecraft will stop executing a program and show an error in these cases:

Using an undefined variable:

## 7. Example Program
// Example Bytecraft program
assign greeting -> "Hello"
assign name -> "Alice"
assign age -> 20

say(greeting + ", " + name + "!") // Hello, Alice!
say("You are " + age + " years old") // You are 20 years old

assign a -> 10
assign b -> 5
say(a + b) // 15
say(a - b) // 5
say(a * b) // 50
say(a / b) // 2


## 8. Running Bytecraft Programs
Open a terminal (PowerShell / CMD)

Navigate to the folder containing your .bc file:

run

bytecraft myprogram.bc


## Summary
Variables: assign name -> value

Print: say(variableOrString)

Arithmetic: + - * / with numbers only

String concatenation: + with strings

Comments: //

Errors: undefined variables, invalid arithmetic, unknown commands

Bytecraft is simple, safe, and designed for beginners to learn programming concepts and create small scripts and for now is still under development.
