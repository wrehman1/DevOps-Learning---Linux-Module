# DevOps-Learning---Linux-Module
so far, I have learnt basic commands that unlock a whole new level of understanding about how systems operate:

• pwd — Shows me the current directory I’m in (“print working directory”)
• ls — Lists the files and folders in my current location
• cd — Allows me to move between directories (“change directory”)
• touch filename.txt — Creates a new empty file
• mkdir foldername — Creates a new directory
• sudo apt update — Updates package lists (critical for system security and software installs!)

I have played the over the wire bandit game which is a Linix based wargame that has an awesome way of sharpening my command-like skills. 
Each level forces you to think critcally, explore system behaviour, and get hands on with tools like ssh, grep, find, cat, chmod, and more.
I accomplished up to level 16 of this game. 

Level 0: Enter the Game
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. 
The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Level 0 -> Level 1
The password for the next level is stored in a file called readme located in the home directory. I used this password to log into bandit1 using SSH. Whenever I found a password for a level, I used the SSH (on port 2220) to log into that level and continued the game.
![image](https://github.com/user-attachments/assets/5390504d-91b7-4758-a826-0ff2eae16bc7)

Level 1 -> Level 2
The password for the next level is stored in a file called ‘-’ located in the home directory
![image](https://github.com/user-attachments/assets/8014dea7-8c13-45fc-81bc-91e8cabd597d)

Level 2 → Level 3
The password for the next level is stored in a file called spaces in this filename located in the home directory.
![image](https://github.com/user-attachments/assets/c88ab245-77f0-4faa-89fe-2abf096ee47e)

Level 3 → Level 4
The password for the next level is stored in a hidden file in the inhere directory.
![image](https://github.com/user-attachments/assets/d960735a-01d7-41eb-a843-d15545bf1b67)

Level 4 → Level 5
The password for the next level is stored in the only human-readablefile in the inhere directory. Tip: if your terminal is messedup, try the “reset” command.
![image](https://github.com/user-attachments/assets/14bcbcbb-7165-4153-a52f-0c1572f46d6d)

Level 5 → Level 6
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
• human-readable
• 1033 bytes in size
• not executable
![image](https://github.com/user-attachments/assets/ab493d50-d6fc-4065-a278-a749c78c04f8)

Level 6 → Level 7
The password for the next level is stored somewhere on the server and has all of the following properties:
• owned by user bandit7
• owned by group bandit6
• 33 bytes in size
![image](https://github.com/user-attachments/assets/130d7f2f-5d04-4efc-9b1b-5a409a3ae2ab)

Level 7 → Level 8
The password for the next level is stored in the file data.txt next to the word millionth.
![image](https://github.com/user-attachments/assets/b1a362d0-204d-4a60-af86-c902aeee7ce5)

Level 8 → Level 9
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
![image](https://github.com/user-attachments/assets/39c47b4d-e3fc-448b-ae18-cc637c6275f3)

Level 9 → Level 10
The password for the next level is stored in the file data.txt in one of the few human-readable strings, beginning with several ‘=’characters.
![image](https://github.com/user-attachments/assets/3767f8d0-e0a5-4256-b07c-04bc75475e0b)

Level 10 → Level 11
The password for the next level is stored in the file data.txt, which contains base64 encoded data
![image](https://github.com/user-attachments/assets/42002755-3012-42d4-9ed2-3b4070a6c0c7)

Level 11 → Level 12
The password for the next level is stored in the file data.txt,where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.
![image](https://github.com/user-attachments/assets/ddc51c57-de95-4507-8c63-19ba4e02159d)

Level 12 → Level 13
The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed.
For this level it may be useful to create a directory under /tmp in which you can work using mkdir. 
For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv
![image](https://github.com/user-attachments/assets/d67e420d-14b5-4d9f-b30f-ee615f93fa1b)
![image](https://github.com/user-attachments/assets/a7256efd-6768-4bf4-a655-044dc4c5265a)

Level 13 → Level 14
The password for the next level is stored in/etc/bandit_pass/bandit14 and can only be read by userbandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level.
![image](https://github.com/user-attachments/assets/6dd039fa-6505-4e52-8b66-459d640135d4)

Level 14 → Level 15
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.
![image](https://github.com/user-attachments/assets/82a160e7-b938-467e-adbd-b54722a16252)

Level 15 → Level 16
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL encryption. 
![image](https://github.com/user-attachments/assets/843b5490-dad9-464e-a90a-c7428006f292)






