![Screenshot_2024-09-19_17_45_09](https://github.com/user-attachments/assets/873ef98a-48e0-445b-b5dc-eb5959ad5b34)

# <h1 align="center">Burpsuite Professional v2025 latest</h1>

<p align="center"> Burp Suite Professional is the web security tester's toolkit of choice. Use it to automate repetitive testing tasks - then dig deeper with its expert-designed manual and semi-automated security testing tools. Burp Suite Professional can help you to test for OWASP Top 10 vulnerabilities - as well as the very latest hacking techniques. Advanced manual and automated features empower users to find lurking vulnerabilities more quickly. Burp Suite is designed and used by the industry's best.</p>

<h3 align="center">

[Overview](https://portswigger.net/burp/pro)
</h3>
 
<br></br>

# Linux Installation
```sh
wget -qO- https://raw.githubusercontent.com/Hackernavi/Burpsuite-Professional/main/install.sh | sudo bash
```
## Run
```sh
burpsuitepro
```
<details><summary>

## Update
</summary>

> optional
```sh
cd
```
```
rm -rf Burpsuite-Professional && wget -qO- https://raw.githubusercontent.com/Hackernavi/Burpsuite-Professional/refs/heads/main/update.sh | sudo bash
```
</details>

<details><summary>
 
## Java Version
</summary>

> select the default java version
```sh
sudo update-alternatives --config java
```               
</details>



---------
# Windows Installation

<br>
 
- Make a `Burp` directory name in `C Drive` for faster access.

- Download [install.ps1](https://codeload.github.com/Hackernavi/Burpsuite-Professional/zip/refs/heads/main) and extract move the file inside to `C:\Burp`

- Open `Powershell` as administrator and execute below command to set Script Execution Policy.


      Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process

- Inside PowerShell go to `cd C:\Burp`

- Now Execute `install.ps1` file in Powershell to Complete Installation.

      ./install.ps1
 
- Change the icon of `Burp-Suite-Pro.vbs` to the given icon 

- Create a shortcut to Desktop. Right Click over `Burp-Suite-Pro.vbs` Go to Shortcut tab, and below there is `Change Icon` tab

- Click there and choose the `burp-suite.ico` from `C:\Burp\`

   <div align="center">
    
    <img src="https://user-images.githubusercontent.com/29830064/230825172-16c9cfba-4bca-46a4-86df-b352a4330b12.png">
</div>

- For Start Menu Entry, copy `Burp-Suite-Pro.vbs` file to 

      C:\ProgramData\Microsoft\Windows\Start Menu\Programs\


 <details><summary>Credit</summary>

* Loader.jar 👉 [h3110w0r1d-y](https://github.com/h3110w0r1d-y/BurpLoaderKeygen)
* Script 👉 [cyb3rzest](https://github.com/cyb3rzest/Burp-Suite-Pro)

</details>
