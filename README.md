# fedora-linux
 
## General Info
I have decided to learn Linux to gain system administration skills. This project will be dedicated to documenting the changes made to the system, until I find a more efficient notetaking solution. 

Coming from macOS, I have exclusively used GitHub on the command line. I want to learn to "live in the terminal" to be more efficient, secure, and create cool things!

I began with a new computer. It contained none of my data, so I created a recovery drive of Windows 11 OS with a USB so that if anything were to break, I could restore the system.

I researched different distros for over a week, and narrowed it down to Linux Mint or Fedora Linux. Though I am a complete beginner and Mint is often recommended to those with little experience, I decided to go with Fedora as my first distro. I enjoyed the look and feel of Fedora Workstation (it reminds me of macOS), but chose Fedora Cinnamon due to how customizable it is. It will be fun to unlock its potential as a DE. 

## Project Learning Goals
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

## Post-Installation Issues

Updated the system from the command line with `sudo dnf upgrade`. Had to reboot after an error took place. Everything was fine after rebooting.

I understand there are some issues with the battery draining too fast on the Dell XPS 13. This can worsen when changing from Windows to Linux. After doing some research, I found that Dell computers often come with RAID on (for seemingly no reason). In order to improve this issue I did the following: 

1. Reboot and press F2 to configure BIOS.
2. Enter Storage from the settings screen.
3. Change SATA setting from RAID on to AHCI.
4. Click accept on the alert pop up, then apply changes and hope for the best. 

I believe the battery is lasting much longer now. I've had the laptop open and going to sleep while unplugged and it is still relatively full. 

Update 08/03/23: Battery is incredibly efficient since the change. 

## To-do

* [Enable RPM Fusion](https://docs.fedoraproject.org/en-US/fedora/latest/system-administrators-guide/package-management/DNF/)
* [Install password manager](https://www.makeuseof.com/install-set-up-bitwarden-linux/)
* [Create a snapshot of my current system](https://fedoraproject.org/wiki/Btrfs)
* [Customize the desktop environment](https://www.youtube.com/watch?v=AnNx-Se9wkc)
* [Download frequently used apps using package manager](https://docs.fedoraproject.org/en-US/fedora/latest/system-administrators-guide/package-management/DNF/#sec-Installing)
* [Log into my accounts and manage users](https://docs.fedoraproject.org/en-US/fedora/latest/system-administrators-guide/basic-system-configuration/Managing_Users_and_Groups/)
* [Create my development environments for Python and JavaScript](https://code.visualstudio.com/download)
* [Figure out basic Linux command line](https://linuxjourney.com/)
* [Research best security practices for linux](https://fedoraproject.org/wiki/SecurityBasics)
* [Write a script](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/) that helps me [log all changes made to the system](https://www.reddit.com/r/linuxquestions/comments/q2pnpx/any_way_to_track_all_of_the_changes_made_to_a/)
* [Write scripts that automate repetitive processes](https://opensource.com/article/19/12/automation-bash-scripts)
