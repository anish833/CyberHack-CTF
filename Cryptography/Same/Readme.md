Challenge:
```
My mother is very smart so i am. It's because of ......................
Note: wrap the decoded text in cyberhack{} and replace 0 with _
Cipher:
AGAATCCATACAAGTAGTAGAACGACAATCAAGACATTGAGACAGTTGAGAATCTTGCGAATGCCACACTTGACGACAATCACACAG
```

It took me a long time figuring out what was the cipher. After banging my head against the wall I found that it is a DNA cipher. You can identify it by seeing the
sequence that have only A, C, G, T as of our cipher. I found the mapping

<img src="dna_codes.png" />

Decode this with sets of three always and decoding this I found the flag

flag: ```cyberhack{intelligence_is_in_your_genes}```
