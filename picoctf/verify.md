Description
People keep trying to trick my players with imitation flags. I want to make sure they get the real thing! I'm going to provide the SHA-256 hash and a decrypt script to help you know that my flags are legitimate.
ssh -p 58220 ctf-player@rhea.picoctf.net
Using the password 6dd28e9b. Accept the fingerprint with yes, and ls once connected to begin. Remember, in a shell, passwords are hidden!
Checksum: 03b52eabed517324828b9e09cbbf8a7b0911f348f76cf989ba6d51acede6d5d8
To decrypt the file once you've verified the hash, run ./decrypt.sh files/<file>.

hint1: Checksums let you tell if a file is complete and from the original distributor. If the hash doesn't match, it's a different file.
hint2: You can create a SHA checksum of a file with sha256sum <file> or all files in a directory with sha256sum <directory>/*.
hint3: use grep


Solution

![alt text](image-1.png)

step1: find the coressponding hash in checksum in the files directory
step2: decrypt the file using decrypt.sh

![alt text](image-2.png)
![alt text](image-4.png)


![alt text](image-5.png)



![alt text](image-6.png)