# Command Line Basics

Highlights from the article https://terokarvinen.com/2020/command-line-basics-revisited/
- The article outlines some basic useful information and commands needed to use in the Terminal.
- As was written in the article I also found that in particularly the tab function is helpful to avoid types

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
- Clicked start in Virtual Box to start the created virtual machine and pressed enter at the boot screen to boot from the Live environment
<img width="423" height="241" alt="Screenshot 2025-11-11 170910" src="https://github.com/user-attachments/assets/e3b28ffd-fb0f-408e-b368-84aebb04d1e7" />
<img width="643" height="569" alt="Screenshot 2025-11-11 171016" src="https://github.com/user-attachments/assets/1eb07895-23ca-4b21-8934-703432a87a69" />

- After a bit of waiting time started the Debian installation
- <img width="603" height="544" alt="Screenshot 2025-11-11 171801" src="https://github.com/user-attachments/assets/bf43c6a8-9e6f-4f98-a24b-78ea3cafbdcc" />
Chose Language, location, keyboardlayout, and choose to erase the disk (on the virtual machine), and set up the PC details and a user
<img width="1179" height="874" alt="image" src="https://github.com/user-attachments/assets/942fafc3-86ef-4ef1-b4da-e278f5088cb5" />

##### Logging in with the new user
- Initially i had to log in with the default debian account
- then I restarted the Debian in the virtual machine to log in with my own user

# Cracking Passwords with Hashcat

I followed the instructions at
Highlights from https://terokarvinen.com/2020/command-line-basics-revisited/](https://terokarvinen.com/2022/cracking-passwords-with-hashcat/
- Learned the value of tab the hard way
- I really could have used a copy-paste possibility between the real and virtual machine for entering the hash initially
- But atleast the second time I could use arrow up to reuse it from earlier


<img width="1050" height="625" alt="image" src="https://github.com/user-attachments/assets/5aa449af-4532-4d17-9f39-f30d6dfa146a" />


<img width="1056" height="626" alt="image" src="https://github.com/user-attachments/assets/b2fb3949-903d-4a79-8250-2eda8577c899" />


<img width="1053" height="626" alt="image" src="https://github.com/user-attachments/assets/9f18e93a-bea3-4646-bcad-1be4b4b04e6f" />

