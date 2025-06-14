# Windows Commands Mission  
*Author: Tredarion Hampton • Last updated: 2025-06-14*

## Windows Commands

A "Windows command" refers to any command or instruction entered into Command Prompt (CMD) or PowerShell on a Windows operating system. Windows commands are used to perform various tasks, such as navigating the file system, managing files and directories, executing programs, configuring system settings, and more. Here are Windows equivalents to common Linux commands:

### Core Command Equivalents

1. **dir / Get-ChildItem:** Lists the contents of a directory (Linux: ls)
2. **cd / Set-Location:** Changes the current directory (Linux: cd)
3. **cd / pwd / Get-Location:** Prints the current working directory (Linux: pwd)
4. **mkdir / New-Item -ItemType Directory:** Creates a new directory (Linux: mkdir)
5. **rmdir / Remove-Item:** Removes directory (Linux: rmdir)
6. **del / Remove-Item:** Removes files or directories (Linux: rm)
7. **copy / Copy-Item:** Copies files or directories (Linux: cp)
8. **move / Move-Item:** Moves or renames files or directories (Linux: mv)
9. **type / Get-Content:** Displays the contents of a file (Linux: cat)
10. **more / Out-Host -Paging:** Allows you to view the contents of a file page by page (Linux: less)
11. **findstr / Select-String:** Searches for patterns in files (Linux: grep)
12. **icacls / Set-Acl:** Changes the permissions of a file or directory (Linux: chmod)
13. **takeown / Set-Owner:** Changes the owner of a file or directory (Linux: chown)
14. **tasklist / Get-Process:** Lists currently running processes (Linux: ps)
15. **taskkill / Stop-Process:** Terminates a process by process ID (PID) (Linux: kill)
16. **runas / Start-Process -Verb RunAs:** Executes a command with administrator privileges (Linux: sudo)
17. **help / Get-Help:** Displays help for a command (Linux: man)
18. **doskey /history / Get-History:** Displays a list of recently executed commands (Linux: history)

> These are just a few examples, and there are many more Windows commands available for various purposes. Each command typically has its own set of options and arguments to customize its behavior. You can use the "help" command followed by the name of a command, or "Get-Help" in PowerShell, to learn more about its usage and options.

## Learning Path

### 1. Start with the Basics
- Learn fundamental commands for navigating the file system (**dir/Get-ChildItem, cd/Set-Location, pwd/Get-Location**)
- Practice creating, copying, moving, and deleting files and directories (**mkdir/New-Item, copy/Copy-Item, move/Move-Item, del/Remove-Item**)
- Familiarize yourself with file manipulation commands (**type/Get-Content, more/Out-Host -Paging, findstr/Select-String**)

### 2. Understand Permissions and Ownership
- Learn how to manage file permissions and ownership using commands like **icacls** and **takeown**
- Understand NTFS permissions vs Linux permissions model
- Practice with **Get-Acl** and **Set-Acl** in PowerShell

### 3. Explore Text Processing Tools
- Learn how to manipulate and process text using PowerShell cmdlets and operators
- Practice filtering and searching text using **findstr** (CMD) and **Select-String** (PowerShell)
- Explore PowerShell's object pipeline for advanced text manipulation

### 4. Work with Processes
- Understand how to manage processes using commands like **tasklist/Get-Process**, **taskkill/Stop-Process**, and **wmic process**
- Monitor system resources with **Task Manager** command-line alternatives

### 5. Get Comfortable with Package Management
- Learn how to install, update, and remove software packages using:
  - **winget** (Windows Package Manager)
  - **choco** (Chocolatey, third-party)
  - **Install-Module** (PowerShell modules)

### 6. Explore System Information and Monitoring
- Learn how to gather system information:
  - **systeminfo** - displays system configuration
  - **hostname** - displays computer name
  - **wmic** - Windows Management Instrumentation command-line
  - **Get-ComputerInfo** - comprehensive system information (PowerShell)
- Monitor system resources:
  - **perfmon** - Performance Monitor
  - **Get-Counter** - performance counters (PowerShell)

### 7. Practice PowerShell Scripting
- Experiment with writing PowerShell scripts (.ps1 files) to automate tasks
- Learn about variables, control structures (if-else, loops), and functions
- Understand execution policies and script signing

### 8. Understand Input/Output Redirection and Pipes
- Learn how to redirect input/output using symbols:
  - **>** (output redirection)
  - **>>** (append)
  - **<** (input redirection)
  - **|** (pipe)
- Practice combining multiple commands using pipes to perform complex tasks

### 9. Explore Networking Commands
- Learn how to troubleshoot network connectivity:
  - **ping** / **Test-Connection**
  - **tracert** / **Test-NetConnection -TraceRoute**
  - **netstat** / **Get-NetTCPConnection**
  - **nslookup** / **Resolve-DnsName**
- Understand basic network configuration:
  - **ipconfig** / **Get-NetIPConfiguration**
  - **netsh** / **Get-NetAdapter**
  - **route** / **Get-NetRoute**

### 10. Stay Curious and Practice Regularly
- Continuously explore new commands and their options
- Practice using Windows commands regularly to reinforce your learning
- Transition between CMD and PowerShell to understand both environments

## Resources
- [PowerShell Documentation](https://learn.microsoft.com/powershell/)
- [Windows Commands Reference](https://learn.microsoft.com/windows-server/administration/windows-commands/windows-commands)
- [SS64 Command Line Reference](https://ss64.com/nt/)
- [PowerShell Gallery](https://www.powershellgallery.com/)

## Submission
Create a PowerShell script that demonstrates at least 10 different Windows commands from the list above. Include comments explaining what each command does. Save as `windows-commands-demo.ps1` and commit to `submissions/<handle>/windows-commands/`.