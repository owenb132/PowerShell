# PowerShell

My collection of useful modules, scripts, snippets and templates written by myself.

## Description

Automate all the things! 

## Module

#### How to install the module?

1. Download the [latest Release](https://github.com/BornToBeRoot/PowerShell/releases/latest)
2. Copy the folder [Module\LazyAdmin](Module/LazyAdmin) to `C:\Users\%username%\Documents\WindowsPowerShell\Modules\`
3. Open up a PowerShell as an admin and set the execution policy: `Set-ExecutionPolicy RemoteSigned`
4. Import the Module with the command `Import-Module LazyAdmin` (Maybe add this command to your PowerShell profile) 

#### Available functions

| Function | Description | Help | 
| :--- | :--- | :---: |
| [Convert-IPv4Address](Module/LazyAdmin/Convert-IPv4Address.ps1) | Convert an IPv4-Address to Int64 and vise versa | [:book:](Documentation/Convert-IPv4Address.README.md) |
| [Convert-Subnetmask](Module/LazyAdmin/Convert-Subnetmask.ps1) | Convert a subnetmask to CIDR and vise versa | [:book:](Documentation/Convert-Subnetmask.README.md) |
| [Get-InstalledSoftware](Module/LazyAdmin/Get-InstalledSoftware.ps1) | Get all installed software with DisplayName, Publisher and UninstallString | [:book:](Documentation/Get-InstalledSoftware.README.md) |
| [Get-WindowsProductKey](Module/LazyAdmin/Get-WindowsProductKey.ps1) | Get the Windows product key and some usefull informations about the system | [:book:](Documentation/Get-WindowsProductKey.README.md) |
| [Get-WLANProfile](Module/LazyAdmin/Get-WLANProfile.ps1) | Get WLAN profiles, include password as SecureString or as plain text | [:book:](Documentation/Get-WLANProfile.README.md) |
| [New-IPv4Subnet](Module/LazyAdmin/New-IPv4Subnet.ps1) | Calculate a subnet based on an IP-Address and the subnetmask or CIDR | [:book:](Documentation/New-IPv4Subnet.README.md) |
| [New-RandomPassword](Module/LazyAdmin/New-RandomPassword.ps1) | Generate passwords with a freely definable number of characters | [:book:](Documentation/New-RandomPassword.README.md) |
| [New-RandomPIN](Module/LazyAdmin/New-RandomPIN.ps1) | Generate a PIN with a freely definable number of numbers | [:book:](Documentation/New-RandomPIN.README.md) |
| [Search-StringInFiles](Module/LazyAdmin/Search-StringInFiles.ps1) | Find a string in one or multiple files | [:book:](Documentation/Search-StringInFiles.README.md) |
| [Split-IPv4Subnet](Module/LazyAdmin/Split-IPv4Subnet.ps1) | Split a subnet in multiple subnets with given subnetmasks | [:book:](Documentation/Split-IPv4Subnet.README.md) |
| [Test-IsFileBinary](Module/LazyAdmin/Test-IsFileBinary.ps1) | Test if a file is binary | [:book:](Documentation/Test-IsFileBinary.README.md) |
| [Update-StringInFiles](Module/LazyAdmin/Update-StringInFiles.ps1) | Replace a string in one or multiple files | [:book:](Documentation/Update-StringInFiles.README.md)

## Scripts

| Script | Description | Help | 
| :--- | :--- | :---: |
| [Convert-IPv4Address.ps1](Scripts/Convert-IPv4Address.ps1) | Convert an IPv4-Address to Int64 and vise versa | [:book:](Documentation/Convert-IPv4Address.README.md) |
| [Convert-Subnetmask.ps1](Scripts/Convert-Subnetmask.ps1) | Convert a subnetmask to CIDR and vise versa | [:book:](Documentation/Convert-Subnetmask.README.md) |
| [Get-InstalledSoftware.ps1](Scripts/Get-InstalledSoftware.ps1) | Get all installed software with DisplayName, Publisher and UninstallString | [:book:](Documentation/Get-InstalledSoftware.README.md) |
| [Get-WindowsProductKey.ps1](Scripts/Get-WindowsProductKey.ps1) | Get the Windows product key and some usefull informations about the system | [:book:](Documentation/Get-WindowsProductKey.README.md) |
| [Get-WLANProfile.ps1](Scripts/Get-WLANProfile.ps1) | Get WLAN profiles, include password as SecureString or as plain text | [:book:](Documentation/Get-WLANProfile.README.md)
| [New-IPv4Subnet](Scripts/New-IPv4Subnet.ps1) | Calculate a subnet based on an IP-Address and the subnetmask or CIDR | [:book:](Documentation/New-IPv4Subnet.README.md) |
| [New-RandomPassword.ps1](Scripts/New-RandomPassword.ps1) | Generate passwords with a freely definable number of characters | [:book:](Documentation/New-RandomPassword.README.md)
| [New-RandomPIN.ps1](Scripts/New-RandomPIN.ps1) | Generate a PIN with a freely definable number of numbers | [:book:](Documentation/New-RandomPIN.README.md) |
| [Search-StringInFiles.ps1](Scripts/Search-StringInFiles.ps1) | Find a string in one or multiple files | [:book:](Documentation/Search-StringInFiles.README.md) |
| [Split-IPv4Subnet](Scripts/Split-IPv4Subnet.ps1) | Split a subnet in multiple subnets with given subnetmasks | [:book:](Documentation/Split-IPv4Subnet.README.md) |
| [Test-IsFileBinary.ps1](Scripts/Test-IsFileBinary.ps1) | Test if a file is binary | [:book:](Documentation/Test-IsFileBinary.README.md) |
| [Update-StringInFiles.ps1](Scripts/Update-StringInFiles.ps1) | Replace a string in one or multiple files | [:book:](Documentation/Update-StringInFiles.README.md) |

## Snippets

| Snippet | Description | 
| :--- | :--- | :---: |
| [custom_psobject.ps1](Snippets/custom_psobject.ps1) | Custom PSObject to process or return as result |
| [get_console_colors.ps1](Snippets/get_console_colors.ps1) | Show all foreground and background console colors |
| [get_sourcecode_of_a_function.ps1](Snippets/get_sourcecode_of_a_function.ps1) | Get the sourcecode of an existing function | 
| [press_any_key_to_continue.ps1](Snippets/press_any_key_to_continue.ps1) | Wait for user interaction e.g. at the end of a script | 
| [regex_validate_pattern.ps1](Snippets/regex_validate_pattern.ps1) | Collection of regex pattern |
| [self_elevating_script.ps1](Snippets/self_elevating_script.ps1) | Self elevate a PowerShell script/console with parameter |
| [send_mail_message.ps1](Snippets/send_mail_message.ps1) | Send a mail message via PowerShell |
| [use_exchange_2010_management_shell.ps1](Snippets/use_exchange_2010_management_shell.ps1) | Use Exchange 2010 Management Shell in script |

## Templates

| Template | Description |
| :--- | :--- |
| [Default.ps1](Templates/Default.ps1) | Default template for all new scripts |
| [Default.README.md](Templates/Default.README.md) | Default template for script/function documentation on GitHub |
| [RunspacePool.ps1](Templates/RunspacePool.ps1) | Run code asynchron in a RunspacePool - more efficient than PSJobs |
