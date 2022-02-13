# Brainfuck 🧠 
A simple yet functional Brainfuck interpreter in C.

## Brainfuck Programs

### Hello World
```bf
++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.
```
### Sierpinski triangle
```bf
++++++++[>+>++++<<-]>++>>+<[-[>>+<<-]+>>]>+[-<<<[->[+[-]+>++>>>-<<]<[<]>>++++++[<<+++++>>-]+<<++.[-]<<]>.>+[>>]>+]
```
### FizzBuzz
```bf
++++++++++[>++++++++++<-]>>++++++++++>->>>>>>>>>>>>>>>>-->+++++++[->++
++++++++<]>[->+>+>+>+<<<<]+++>>+++>>>++++++++[-<++++<++++<++++>>>]++++
+[-<++++<++++>>]>>-->++++++[->+++++++++++<]>[->+>+>+>+<<<<]+++++>>+>++
++++>++++++>++++++++[-<++++<++++<++++>>>]++++++[-<+++<+++<+++>>>]>>-->
---+[-<+]-<[+[->+]-<<->>>+>[-]++[-->++]-->+++[---++[--<++]---->>-<+>[+
+++[----<++++]--[>]++[-->++]--<]>++[--+[-<+]->>[-]+++++[---->++++]-->[
->+<]>>[.>]++[-->++]]-->+++]---+[-<+]->>-[+>>>+[-<+]->>>++++++++++<<[-
>+>-[>+>>]>[+[-<+>]>+>>]<<<<<<]>>[-]>>>++++++++++<[->-[>+>>]>[+[-<+>]>
+>>]<<<<<]>[-]>>[>++++++[-<++++++++>]<.<<+>+>[-]]<[<[->-<]++++++[->+++
+++++<]>.[-]]<<++++++[-<++++++++>]<.[-]<<[-<+>]+[-<+]->>]+[-]<<<.>>>+[
-<+]-<<]
```

### Usage
From a terminal
```
Brainfuck.exe -i ++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.

>>> Hello World!
```

Interpret files
```
Brainfuck.exe -f HelloWorld.bf

>>> Hello World!
```

## Todo
> Add in optimizations such as pre-computing the jump table for loops.

> Clean up File I/O
