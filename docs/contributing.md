# Contributing

## Scope

The Unified Write Filter module exists to control UWF on Windows 10 computers.
The uwfmgr.exe command-line application is great for managing one machine but terrible for remote administration. 
The goal of this module is to surface the WMI properties and methods in an easy-to-use set of commandlets. 
Any feature or pull requests should keep this senario in mind.

## Tools

The software needed for development is as follows:

* PowerShell 5.1
* [Git for Windows](https://github.com/RamblingCookieMonster/PSDepend)

Recommended: 

* [Visual Studio Code](https://code.visualstudio.com/)
* [ms-vscode.powershell](https://github.com/PowerShell/vscode-powershell) VSCode extension


The PowerShell modules needed are as follows:

* [PSDepend](https://github.com/RamblingCookieMonster/PSDepend)
* [PSake](https://github.com/psake/psake)
