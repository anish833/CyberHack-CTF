Challenge
```
Ciphertext link: https://drive.google.com/file/d/17DyAR9ZL5lho6D9RRX3OVXDP41emkW5w/view?usp=sharing
```

Going to the link gave me this 
```
z*zz**z*z*zz***zzz**z*zzz*z*z***z*zzz*z*z*z**z*zz*zz**zzz*z*zz**z*zz***zz*zzzz*zz*z*zzz*z*z*z***z*zzz***zz**zz*zzz**z
z**zz**zz**z*zz****zz**z*zzz*z**z*zz*z*z**zzz**z**zzz**zz**z*zz*z*zz*z*z*z*z*zz***zz*zz**z*z*z**z*zz*z*z**zzz**z**zzz
**z*z*z*z*zz*zz*z*zz*zz*zz****z*zz*z*zzz**zz*zz*z*z*zzz*zz*z**z*z**z*zz*zz**zzz*z*z*zzz*zzz*z*z*zzz**zzz**z**zz*z*zzz*
zz****z*zz****z*zz****z*zz****z*
```

I was on this challenge for some times figuring out if this is a esoteric language but at last I saw this cipher it has only two characters
and binary numbers have also two numbers and the challenge name is ```SUBSway``` so i think of substituting values. So i replaced all z with 0
and all * with 1 it looked like
```
0100110101001110001101000101011101000101010110100100110001010011010011100100001001010001010101110100011100110010001100110011
0011010011110011010001011010010101100011011000110011010010100101010101001110010011010101101001010110001101100011010101010010
0101001001001111010010100011001001010100010010110101101001001100010101000100010101000110001101100101000100111101001111010011
110100111101
```

Decoding this with cyberchef gave me ```MN4WEZLSNBQWG233O4ZV63JUNMZV65RROJ2TKZLTEF6Q====``` a base64 string, decoding this again gave me the flag

flag : ```cyberhack{w3_m4k3_v1ru5es!}```
