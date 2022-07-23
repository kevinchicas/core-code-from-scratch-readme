*<center> <h2>Your date of birth in the Matrix?</h2> </center>*

---
My date of birth is March 13th, 1996.

This is the way a converted from decimal to binary

[![Captura.jpg](https://i.postimg.cc/xjL7MgxL/Captura.jpg)](https://postimg.cc/QVx0rgrM)

13 = 1101

3= 11

1996= 11111001100




*<center> <h2> MIPS exercise </h2> </center>*
```assembly
 .data
	      myname: .asciiz "\nKevin Chicas\n"
  .text
	      main:
              li $v0, 4
              la $a0, myname
              syscall
```

```assembly
.data
	      number1: .asciiz "\nAdd a number: "
	      number2: .asciiz "\nAdd a second numer : "
	      result_message: .asciiz "\nResult: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t0, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              add $t2, $t0, $t1

              li $v0, 4
              la $a0 result_message
              syscall

              li $v0, 1
              move $a0, $t2
              syscall
```
---