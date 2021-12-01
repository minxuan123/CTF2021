We intercepted messages between our targets, whom we believed were plotting some evil deeds against the world. It would be Christmas by the time we unwrap it ... 

The higher ups have provided us some clues on how to unravel their schemes:

1. Decoder
(Not decryption!) The real cipher has been vandalized with much rubbish words, we will have to do some cleanup first. You'll know it when you see it.

2. Add some Vinegar Cidher...
Seems like the targets are huge fans of a certain type of ciphers...sometimes they add a second layer!

3. Save our RSAsty brains~
Use the knowledge you have gained from before to crack their final line of defence!

correspondance.txt

<!-- A very brief summary of how the challenge is supposed to be solved, together with a solution program if required (for instructors only, not for your fellow students). -->

The participants have to go through 3 layers/ steps. For the first step, participants have to convert the content in the txt file from ASCII format which will reveal the 2 main paragraphs. The first paragraph requires RSA decryption. From the second paragraph, they have to identify the key “XMAS" (which has been randomly interspersed). They then have to use this key to decrypt the vigenere cipher. This will then reveal a second conversation between the 2 main characters, which hints of the chosen public key e = 65537. They will have to identify the private n values (n1, n2) from the l33k text, and use it for the third step. The third step would require them to use these values (n,e) to decrypt the first paragraph using RSA. They will have to do this possibly using brute force to identify p,q values (for both main characters), to compute the d values (d1, d2), and apply the d for the decryption.