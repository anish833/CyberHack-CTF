Challenge:
```
Ola ! Reverse Engineers , get to work.... (Mazekeen ke kehne pe) https://drive.google.com/file/d/1DL6kOjQhN14sRYcCZVF9DYEmYrw-Hj49/view?usp=sharing
```

The file has the content 
```
Cipher text : ----------]<-<---<-------<---------->>>>+[<<<<+,----------------------,+++++++++++++++++++++++,---,-------------,++++++++++,+++++++,--,--------,----------------,+++++++++,>+++++++++++++++++++,<----,>,<++++,-,++++++++++++++,++++++,>------------------,<---------------,+++++++,--,-----,>++++++++++++++++++,,<----,-,>>---,,<<----------,
```

For those who have played some CTFs will know that it is a esoteric language ```BrainFuck``` but when using brainfuck decoder it didn't work
so spending some time googling I found out that this is ```Reversefuck``` because operands and brackets are used in reverse order so googling for a 
online decoder ```https://www.dcode.fr/reversefuck-language``` and decoding it gave me the flag

flag:```cyberhack{r3v3rse_Engin33rs!!}```
