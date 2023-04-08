# picoCTF_SleuthkitIntro
## !!! DISCLAIMER - THIS PROJECT IS NOT INTENDED TO BE USED IN A BAD WAY AND IS INTENDED ONLY FOR EDUCATIONAL PURPOSES I NEITHER CONDONE NOR TAKE RESPONSIBILITY FOR SOMEONE ELSE'S ACTIONS !!!

A quick walkthrough of picoCTF's "Sleuthkit Intro" room.

1. Firstly we use the utility "mmls", which is the one suggested in the CTF description - mmls (name_of_file)
![SleuthkitIntro](https://user-images.githubusercontent.com/109030111/230676748-4c89d9d5-1290-43fe-8b1a-33cc0efaa979.png)

We can see the length of the Linux partition under the ID of 002 - 0000202752

2. When we've saved our answer we can connect to the picoCTF's machine with the use of the command - nc saturn.picoctf.net (port)
After that we input the lenth of the Linux partition. Finally the flag is shown to us.
![SleuthkitIntro2](https://user-images.githubusercontent.com/109030111/230679422-394b7194-d72e-4a3d-b37c-ed0248513e5c.png)

That wraps up my quick tutorial on the Sleuthkit Intro thank you for reading it and I hope you find it helpful!

By nodlezgucci!
