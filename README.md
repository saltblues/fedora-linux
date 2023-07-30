# fedora-linux

## Table of contents
* [General-info] (#general-info)
* [Project-learning-goals] (#project-learning-goals)
* [Installation] (#installation)
* 

## General info
I have decided to learn Linux to gain system administration skills. This project will be dedicated to documenting the changes made to the system, until I find a more efficient notetaking solution. 

Coming from macOS, I have exclusively used GitHub on the command line. I want to learn to "live in the terminal" to be more efficient, secure, and create cool things!

I began with a new computer. It contained none of my data, so I created a recovery drive of Windows 11 OS with a USB so that if anything were to break, I could restore the system.

I researched different distros for over a week, and narrowed it down to Linux Mint or Fedora Linux. Though I am a complete beginner and Mint is often recommended to those with little experience, I decided to go with Fedora as my first distro. I enjoyed the look and feel of Fedora Workstation (it reminds me of macOS), but chose Fedora Cinnamon due to how customizable it is. It will be fun to unlock its potential as a DE. 

## Project learning goals
* Learn proper documentation practices
* Build a wiki
* Establish a standard installation and setup process that can be replicated with every new system
* Use all of GitHub's tools to manage a complex project
* Live in the command line and learn to use Bash
* Learn basic and advanced system admin skills
* Learn best cybersecurity and networking practices
* Write scripts to automate processes
* Troubleshoot and research issues and errors

## Installation

1. Create a Windows Recovery Drive with a bootable USB for use in case of emergencies. Put it somewhere safe.
2. Download a Fedora Linux ISO to a bootable USB. 
3. Boot from it. I kept getting a persistent error in the verification process, so I decided to skip verify (risky move), but everything worked perfectly.
4. Test the OS and ensure that everything works fine. 
5. Perform a clean install of Fedora after extensive research on everything that could go wrong and hope for the best 🫢
6. Everything works!

## Post-installation issues

Updated the system from the command line with `sudo dnf upgrade`. Had to reboot after an error took place. Everything was fine after rebooting.

I understand there are some issues with the battery draining too fast on the Dell XPS 13. This can worsen when changing from Windows to Linux. After doing some research, I found that Dell computers often come with RAID on (for seemingly no reason). In order to improve this issue I did the following: 

1. Reboot and press F2 to configure BIOS.
2. Enter Storage from the settings screen.
3. Change SATA setting from RAID on to AHCI.
4. Click accept on the alert pop up, then apply changes and hope for the best. 

I believe the battery is lasting much longer now. I've had the laptop open and going to sleep while unplugged and it is still relatively full. 

## To-do

* Customize the desktop environment
* Download frequently used apps using package manager
* Log into my accounts
* Create my development environments for python and javascript
* Figure out basic linux command line 
* Research best security practices for linux