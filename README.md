# Readme for Kali Linux Installation and Security Tasks
This guide provides instructions for completing a series of tasks related to Kali Linux installation and network security. The following tasks will be covered:
1. Installing Kali Linux
2. Getting familiar with the Kali GUI
3. Using Linux commands and discovering what they do
4. Installing target machines and figuring their IP addresses
5. Using Wireshark to capture and inspect network traffic, and applying UNIX file permissions using the command line.

# Prerequisites
Before starting the tasks, you will need:
- A computer with at least 4GB of RAM and 20GB of hard disk space
- A virtual machine software such as VirtualBox or VMware
- The Kali Linux ISO file downloaded from the official website (https://www.kali.org/downloads/)
- Basic knowledge of Linux commands and network security concepts

# Task 1: Installing Kali Linux
1. Create a new virtual machine in your virtual machine software.
2. Select the Kali Linux ISO file as the bootable media.
3. Allocate at least 2GB of RAM and 20GB of hard disk space to the virtual machine.
4. Follow the on-screen instructions to install Kali Linux. Make sure to select the "Graphical Install" option.
5. Once the installation is complete, reboot the virtual machine.

# Task 2: Getting familiar with the Kali GUI
1. Login to the Kali Linux virtual machine.
2. Familiarize yourself with the Kali Linux graphical user interface (GUI) by exploring the various tools and applications available.
3. Get comfortable with the Kali Linux Terminal, which will be your primary interface for completing the remaining tasks.

# Task 3: Using Linux commands and discovering what they do
1. Open the Kali Linux Terminal.
2. Use the ls command to list the contents of the current directory.
3. Use the cd command to change to a different directory.
4. Use the man command to display the manual pages for a specific command.
5. Try out some basic Linux commands like mkdir, touch, cat, and rm, and observe their behavior.

# Task 4: Installing target machines and figuring their IP addresses
1. Download and install virtual machines for various target operating systems, such as Windows or Ubuntu.
2. Power on the target machines and ensure they are connected to the same virtual network as the Kali Linux machine.
3. Use the ifconfig command in Kali Linux to determine the IP addresses of the target machines.
4. Verify connectivity between the Kali Linux machine and the target machines using the ping command.

# Task 5: Using Wireshark to capture and inspect network traffic, and applying UNIX file permissions using the command line
1. Install Wireshark on the Kali Linux machine.
2. Use Wireshark to capture and inspect network traffic between the Kali Linux machine and the target machines.
3. Experiment with various Wireshark filters to isolate specific types of network traffic.
4. Use the chmod command to apply UNIX file permissions to a file or directory on the Kali Linux machine.

# Conclusion
By completing these tasks, you will gain hands-on experience with Kali Linux and basic network security concepts. These skills are valuable for a variety of careers in cybersecurity, including penetration testing, network security administration, and incident response.
