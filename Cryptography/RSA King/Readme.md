Challenge 
```
Beat the king fr major reward..!! Link: https://drive.google.com/file/d/1n0rIwgAKo1VJPLYIONE2W5Ja7EYaIlwm/view?usp=sharing
```

Going to the drive link gave me 
```
c=53828192963022776813296693746940435948427065068498665692317
n=77352089398489850796806144825465619279367942479695474338583
e=65537
```

It will be a classic RSA. I went to factordb to find the factors of n and wrote a python script to solve this
```
#!/usr/bin/env python3

from Crypto.Util.number import inverse

c = 53828192963022776813296693746940435948427065068498665692317
n = 77352089398489850796806144825465619279367942479695474338583
e = 65537

p = 288006371
q = 268577702395652389220258411663628160779012567328573

phi = (p-1)*(q-1)
d = inverse(e,phi)
m = pow(c,d,n)

print(bytes.fromhex(hex(m)[2:]).decode('utf-8'))
```
Running the script gave me the flag

flag: ```cyberhack{RSA_15_l0v3}```
