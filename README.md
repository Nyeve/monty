## MONTY

### The Monty Language
**Monty 0.98 is a scripting language** that is first compiled into **Monty** byte codes (Just like Python). <br> It relies on a unique stack, with specific instructions to manipulate it. **The goal of this project is to <br> create an interpreter for Monty ByteCodes files**.

<img src="https://pbs.twimg.com/media/CFYYWy6UEAE9Ow-.png" width="650" height="auto">

---
### The monty program
**Usage**: ```monty file``` <br>
- where ```file``` is the path to the file containing Monty byte code

---
### Installation
```
git clone https://github.com/edwinogwel/monty
```
### Compilation
```
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```

### Tasks
---
0. Implement the push and pall opcodes <br>
   - ```push``` pushes an element to the stack
   - ```pall``` prints all the values on the stack, starting from the top of the stack
1. Implement the pint opcode
   - ```pint``` prints the value at the top of the stack
2. Implement the pop opcode
   - ```pop``` removes the top element of the stack
3. Implement the swap opcode
   - ```swap``` swaps the top two elements of the stack
4. Implement the add opcode
   - ```add``` adds the top two elements of the stack
5. Implement the nop opcode
   - ```nop``` doesn't do anything
6. Implement the sub opcode
   - ```sub``` subtracts the top element of the stack from the second top element of the stack
7. Implement the div opcode
   - ```div``` divides the second top element of the stack by the top element of the stack
8. Implement the mul opcode
   - ```mul``` multiplies the second top element of the stack with the top element of the stack
9. Implement the mod opcode
   - ```mod``` computes the remainder of the second top element of the stack by the top element
10. Comments
    - When the first non-space char of a line is ```#```, treat the line as a comment
11. Implement the pchar opcode
    - ```pchar``` prints the char at the top of the stack
12. Implement the pstr opcode
    - ```pstr``` prints the string starting at the top of the stack
13. Implement the rotl opcode
    - ```rotl``` rotates the stack to the top
14. Implement the rotr opcode
    - ```rotr``` rotates the stack to the bottom
15. Implement the stack and ```queue``` opcodes
    - ```stack``` sets the format of the data to a stack (LIFO)
    - ```queue``` sets the format of the data to a queue (FIFO)
16. Write a Brainf*ck script that prints ```School```
17. Write a Brainf*ck script that adds two digits given by the user
18. Write a Brainf*ck script multiplies two digits given by the user
19. Write a Brainf*ck script multiplies two digits given by the user
    - And print the result, followed by a new line
---
