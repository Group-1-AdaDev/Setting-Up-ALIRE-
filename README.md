# Setting-Up-ALIRE-on-Ubuntu-
*ALIRE Set-up Session Report.*

Below is a step-by-step download of ALIRE on Ubuntu software that I did in my programming class, guided by my lecturer. 

I first searched on the browser and clicked the following link (AdaCore Gnat Academic Program -https://github.com/GNAT-Academic-Program). 



I then downloaded the file on the website using the link (https://github.com/alire-project/alire/releases/download/v2.0.2/alr-2.0.2-bin-x86_64-linux.zip)and extracted it.
Next, I copied the file from the download's section to home.

I then opened the terminal.
Typed 'nano ~/.bashrc' and pressed 'Enter'. Copied the file from home. 
Typed export PATH="${PATH}:(paste the copied file here) then typed :$PATH" 
Pressed Ctrl+letter O and pressed Enter to save the file.
Press Ctrl +letter x to exit the file.

In the terminal, typed nano ~/.bashrc then pressed Enter. 
Typed source ~/.bashrc then pressed Enter. 
Typed 'which alr' pressed enter.
Typed alr then pressed enter.
Typed alr --help, pressed Enter.
Typed alr init --bin myproj.
Wrote the names of the group members.
After the myproj was initialised successfully, I typed cd myproj, pressed Enter.
Typed Ls then pressed Enter. Response was: No such file or directory.
Then I typed alr build and pressed Enter.

From there, the command given was if i wanted to install AlIRE? (Y/N)
I typed Y then another command came up; which was to press Enter to continue or Ctrl+C to abort. I chose Enter.
The installation started and after a few seconds, then it was successfully installed. 






