Category: Forensics


- Trivial Flag Transfer Protocol


Description

Figure out how they moved the [flag](https://mercury.picoctf.net/static/ed308d382ae6bcc37a5ebc701a1cc4f4/tftp.pcapng).


Hints:

1. What are some other ways to hide data?


Answer:

1. open the pcap file with wireshark with file > export object > TFTP > save all

2. decrypt instruction.txt file with [decrypt online tool](https://cryptii.com/pipes/alphabetical-substitution)

3. and the result = TFTP DOESNT ENCRYPT OUR TRAFFICS O WE MUST DISGUISE OUR FLAG TRANSFER,
FIGURE OUT AWAY TO HIDE THE FLAG AND I WILL CHECK BACK FOR THE PLAN

4. I USED THE PROGRAM AND HID IT WITH - DUEDILIGENCE,CHECKOUT THE PHOTOS

5. after decrypt i check photos with steghide and extract that photos with command "steghide extract -sf picture1.bmp,then picture2.bmp and picture3.bmp with passphrasse "DUEDILIGENCE"

6. after extract picture3.bmp i got the flag.txt file,Gotcha!! u got the flag.


Flag: picoCTF{h1dd3n_1n_pLa1n_51GHT_18375919}