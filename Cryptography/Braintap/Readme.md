Challenge
```
Flag Format: cyberhack{ABCD} Note: All characters are in capital letters without any space.
Cipher link: https://drive.google.com/file/d/12_r6bRztwdiIcUOYrKF6WSpvh7bBugpN/view?usp=sharing
```

Going to the link gave me this
```
++++++++++[>+>+++>+++++++>++++++++++<<<<-]>>>++++++++.----------.+++++++++++++.<++++++++++++++++++.>--------.-----.>+++..<++++++++++.
>+++++++++++++++++++.<+++++++++++++++++++++.<+++.>---------------------.>-.<-------------.<--.>+++++++++++++.++++++.+.++++++++++++++++++.
-------------------------.>---------------.<+++++++++++.<+.>----------------.-----.+++++++++++++.>---.<---.----------.+++++++++++++.<--
.>--------.-----.+++++.>++++++++++++++++++.<++++.>----------------.<------------.>++++++++++++++++.<++++++++.-----.+++++++++++++++++.<+
.>-------.+++++.<++++++++++++++++.---------------.>-----.>----------------.<-------------.>++++++++++++++++.
```

This is a esoteric language known as ```BrainFuck``` so going to ```https://www.dcode.fr/brainfuck-language``` and decoding it gave me
```NDQ0IDggNzc3NyA1NTUgNjY2IDQgNDQ0IDIyMiAyIDU1NSA2NiAy``` it is a base64 string so going to cyberchef and decoding it gave me
```444 8 7777 555 666 4 444 222 2 555 66 2```

It is like the keypad cipher I have solved earlier in this CTF
