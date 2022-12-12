Category: Forensics


- Matryoshka Doll


Description


Matryoshka dolls are a set of wooden dolls of decreasing size placed one inside another. What's the final one? Image: [this](https://mercury.picoctf.net/static/1b70cffdd2f05427fff97d13c496963f/dolls.jpg)

Hints:

1. Wait, you can hide files inside files? But how do you find them?

2. Make sure to submit the flag as picoCTF{XXXXX}


Answer:

1. get forensics tools like binwalk in kali linux

2. and extract the file jpg with command "binwalk -e dolls.jpg" and u got base_image folder and zip file

3. jump into the base_image folder and then extract the 2_c.jpg file and extract 3_c.jpg and 4_c.jpg and u get 2 files flag.txt & zip file

4. read flag.txt and voilla! u got the flag.


Flag: picoCTF{bf6acf878dcbd752f4721e41b1b1b66b}