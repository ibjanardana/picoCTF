Category: Forensics


- Wireshark Doo Do Do


Description

Can you find the flag? [shark1.pcapng](https://mercury.picoctf.net/static/4c996ecfb7fbada15a9799511f24dc99/shark1.pcapng).


Answer: 

1. open pcap file with wireshark and go filter the stream with "tcp.stream eq 5"

2. and analyze the stream with analyze > follow > tcp stream and u got text this

[result tcp stream](/Assets/wireshark%20do.PNG)

3. goto decrypt the ROT13 tools, im prefer online tools [tools](https://rot13.com/) and decrypt "cvpbPGS{c33xno00_1_f33_h_qrnqorrs}"

4. voilla!! u got the flag


Flag: picoCTF{p33kab00_1_s33_u_deadbeef}