<!--KALI LINUX IN MOBILE IN TERMUX COMMANDS-->
Kali Nethunter Installation : <br>
Step 1:Install “Termux” from Play Store.

Termux: You can download it from the Play Store.<br>

 Termux download link: https://play.google.com/store/apps/details?id=com.termux

Step 2: Update and Upgrade Termux.

Open the Termux app and type the following commands one by one:<br>
```html
apt update
apt upgrade -y
```
<br>
These commands will update and upgrade the Termux package repository and Termux itself.
<br>  
Step 3: Allow Termux to access storage.

Type the following command to give Termux access to the device storage:<br>

```html
termux-setup-storage
```
<br>
This will prompt you to allow storage access. Grant the permission to proceed. <br>

Step 4: Install the required packages.

Type the following command to install the “wget” package: <br>
```
pkg install wget
```
<br>

Step 5: Download and Install Kali Nethunter.

Type the following commands one by one: <br>
```
wget -O install-nethunter-termux https://offs.ec/2MceZWr
```
<br>

```
chmod +x install-nethunter-termux
```
<br>

```
./install-nethunter-termux
```
<br>
These commands will download and install Kali Nethunter on your device. <br>

<img src="kali linux.jpg"/> <br>
NetHunter for Termux installed successfully . . . <br>

_Congratulations! You have successfully installed Kali Nethunter on your Android device using Termux without root access._ <br>


_Let's Conclude
In conclusion, installing Kali Linux on Android using Termux without root access is a great way to get started with hacking and cybersecurity. However, please use it responsibly and only for ethical purposes. Also, keep in mind the limitations and the need for sufficient resources for optimal performance._

I hope you found this guide helpful. Happy hacking! <br>
