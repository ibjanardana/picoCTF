Category: General Skills


Description

Can you invoke help flags for a tool or binary? This 
<https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm>
program has extraordinarily helpful information...

Hints:
1. This program will only work in the webshell or another Linux computer.

2. To get the file accessible in your shell, enter the following in the Terminal prompt: $ wget https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm

3. Run this program by entering the following in the Terminal prompt: $ ./warm, but you'll first have to make it executable with $ chmod +x warm

4. -h and --help are the most common arguments to give to programs to get more information from them!

5. Not every program implements help features like -h and --help.


Answer:

1. download file with " wget https://mercury.picoctf.net/static/fc1d77192c544314efece5dd309092e3/warm " in your webshell.

2. chmod +x ./warm

3. run ./warm -h

4. gotcha!! u got the flag


Flag: picoCTF{b1scu1ts_4nd_gr4vy_6635aa47}
