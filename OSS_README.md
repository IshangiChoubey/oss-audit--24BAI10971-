**Open Source Software Lab - Shell Script Project**

**Student Information**

Name - Ishangi Choubey  
Roll Number - 24BAI10971

**Chosen Software**

VLC Media Player  
Free and Open-Source Media Player  
Supports various audio and video formats

**Project Description**

The project comprises of **five shell scripts** to explore Linux system information, package management, file auditing, log analysis, and the philosophy of open-source.  

**Scripts Overview**
**Script 1: System Identity Report**
Displays system information such as:
Kernel Version  
Logged-in User  
System Uptime  
Linux Distribution  
Current Date  
Also includes the student's name and the chosen software.  
**Script 2: FOSS Package Inspector**
Checks if a package is installed or not.  
Displays:
Version  
Maintainer  
Description  
Also includes a small note on the philosophy of open-source in the form of a case statement.  
**Script 3: Disk and Permission Auditor**
Scans the permissions of various system directories.  
Scans:
/etc  
/var/log  
/home  
/usr/bin  
/tmp  
Displays:
Permissions  
Owner  
Group  
Directory Size  
Also checks the VLC configuration directory.  
**Script 4: Log File Analyzer**
Takes a log file as the input.  
Counts the number of occurrences of a specified keyword.  
(Default keyword is 'error'.)  
Displays:
Total matches  
Last 5 matches  
**Script 5: Open Source Manifesto Generator**
Takes user inputs for:
Tool  
Meaning of freedom  
Idea to build  
Generates the manifesto and writes it to a file.  

**Dependencies Required**
Ensure the availability of the following tools on your Linux system:
- bash
- dpkg
- lsb_release
- awk
- grep
- du
- whoami
- uptime

To install the tools, use the following commands:
```bash
sudo apt update
sudo apt install lsb-release coreutils
```
### How to Run the Scripts

**Step 1: Give execute permission**

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```
### Run Script 1

```bash
./script1.sh
```
---
### Run Script 2

```bash
./script2.sh
```
---
### Run Script 3

```bash
./script3.sh
```
---
### Run Script 4

```bash
./script4.sh <logfile> [keyword]
```
**Example**

```bash
./script4.sh log.txt error
```
---
### 🔹 Run Script 5

```bash
./script5.sh
```
Follow the prompts to create your manifesto.
### Notes
- All scripts must be run from the same directory.
- Script 4 must be run with a valid text/log file.
- Linux is case-sensitive. File names must be spelled exactly as they are named.
### Conclusion
This project has demonstrated how shell scripts can be used for system monitoring and automation, while also providing a better understanding of open-source concepts within a Linux system.