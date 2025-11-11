# Command Line Basics

Highlights from https://terokarvinen.com/2020/command-line-basics-revisited/

The article outlines some basic useful information and commands needed to use in the Terminal
- ...

# Installing Linux on a virtual machine

The purpose with this task was to setup a secure environment for exploring basic hacking methods.

##### First I downloaded the following files: 
- Virtual box from https://virtualbox.org/  
- Linux Debian 13-Trixie installation from wwww.debian.org Download "Live Xfce" directly from [here](https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/debian-live-13.1.0-amd64-xfce.iso) 
 
##### Then I installed Virtual Box version 7.2.4 (amd64)
- I got a warning about a missing Python Core package, which could be installed later:
 
<img width="523" height="419" alt="Screenshot 2025-11-05 200619" src="https://github.com/user-attachments/assets/4641b893-025a-4918-aafd-6cf8e775260c" /> 
 
*The package was not needed for the current task, but may ofcourse be needed to do later in the course*
 
- The installation completed:

<img width="486" height="391" alt="image" src="https://github.com/user-attachments/assets/411446c4-e256-4b14-b42e-a0f21b67c7e1" /> 
 
##### Then I used Virtual Box to create a virtual partition for installing Debian
 
<img width="388" height="160" alt="Screenshot 2025-11-11 165305" src="https://github.com/user-attachments/assets/aa454ab9-8046-4870-86e3-31766dc83e98" /> 
 
<img width="793" height="548" alt="Screenshot 2025-11-11 170615" src="https://github.com/user-attachments/assets/3c2651e9-7050-42eb-b233-ddd2126aad7a" />

 
- I entered the virtual machine name, checked location, selected the Bebian image for the linux installation, selected the OS version Debian 13 Trixie (64 bit), and **un**selected the "Proceed with Unattended installation" checkbox
- But this time around, when only collecting screenshots, I forgot to specify the virtual hardware and virtual hard disk. But on my previous rounds I have set them to:
  - Memory to 4MB or 8MB
  - A couple of extra CPUS
  - Min. 40 GB harddrive
    *As this is my Xth time doing this (on several different machines), I am **not** starting over again, just for the screenshots*

##### Then I installed Debian on the virtual partition 
- I clicked start in Virtual Box to start the created virtual machine and pressed enter at the boot screen to boot from the Live environment
<img width="423" height="241" alt="Screenshot 2025-11-11 170910" src="https://github.com/user-attachments/assets/e3b28ffd-fb0f-408e-b368-84aebb04d1e7" />
<img width="643" height="569" alt="Screenshot 2025-11-11 171016" src="https://github.com/user-attachments/assets/1eb07895-23ca-4b21-8934-703432a87a69" />

<img width="423" height="241" alt="image" src="https://github.com/user-attachments/assets/0e89865e-d486-4ea0-b460-5773fc9cd472" />
- Pressed Enter to boot from the live 
<img width="643" height="569" alt="image" src="https://github.com/user-attachments/assets/fa5aeb31-be36-48a4-bcf3-066a0bbfa508" />
- and after a minute starting the Debian installation
- <img width="637" height="591" alt="image" src="https://github.com/user-attachments/assets/5a784c97-395d-4190-a2ad-a06001c60bd4" />
Choosing Language, location, keyboardlayout, and Proceeding to choose to erase the disk (on the virtual machine)
<img width="1179" height="874" alt="image" src="https://github.com/user-attachments/assets/942fafc3-86ef-4ef1-b4da-e278f5088cb5" />

- I installed Virtualbox from https://virtualbox.org/
- 

# Cracking Passwords with Hashcat

Highlights from https://terokarvinen.com/2020/command-line-basics-revisited/](https://terokarvinen.com/2022/cracking-passwords-with-hashcat/
-

