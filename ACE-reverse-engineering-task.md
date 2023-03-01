# CyberSecurity Task: Reverse Engineering
*Reverse engineer the given ELF binary and find out the flag inside the code.*<br>
*Link to the file : https://drive.google.com/drive/folders/15j_HeBuZRjAJw8F5IrbOR1IFb9_NfkV_?usp=share_link*<br>
*This task was given to me by my mentor Ayan Ambesh.*

In this writeup i will describe my approach reverse engineering the given binary and finding the flag inside the code.

## Step 1:
When you will go to the given link you will see a file named "reverse_me" with no extensions or file type. As said in the task that it is an ELF file which means it is Executable Linux Format and it only can be executed in linux. So I downloaded it and the first thing that came to my mind was to confirm that it is an ELF and which type of ELF it is. <br>
*So the command i used for that was "file reverse_me"*
![](images/rev1.png)