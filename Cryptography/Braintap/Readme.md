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

<img src = 'https://camo.githubusercontent.com/0a09b3f773f371310cba6af9578b5f296a1864de4554760078d0044cb645ea0d/68747470733a2f2f656e637279707465642d74626e302e677374617469632e636f6d2f696d616765733f713d74626e3a414e643947635153795378486a4d4676383058577037344c5a7066726e41726f3661314d4c7165463146337a706775413550475357396f76'/>

Decoding this gave the flag and the challenge says all should be capital without space

flag: ```cyberhack{ITSLOGICALNA}```
