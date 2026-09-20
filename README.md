# 🚀 A Guide on How to Activate Windows 11 Pro for Free

Welcome to this step-by-step guide on how to upgrade and activate Windows 11 Pro on your system for free!

---

## ❓ Why Upgrade to Windows 11 Pro?
By upgrading to Windows 11 Pro, you get access to advanced features such as:
- **🔒 BitLocker Drive Encryption:** Protect your personal files and drive data.
- **🖥️ Remote Desktop Hosting:** Host your device as a Remote Desktop which can be accessed through the internet.
- **⚙️ Advanced Management Features:** Group Policy Management, Enterprise capabilities, and more.

---

## 🔄 Am I Able to Switch From Any Other Edition to Pro?
**The answer is yes!** You can switch from almost any Windows edition (like Home or Home Single Language) to Pro completely for free!

---

## 📌 Note for Users With Unactivated Pro Edition
If you already have **Windows 11 Pro installed but not activated**, you can skip directly to the **[Activating Windows Pro](#-activating-windows-pro)** section below!

---

## 🛠️ Getting Started

First, you need to open Command Prompt (CMD) as Administrator.

1. Press the following keys on your keyboard:  
   `Windows-logo key + R`

2. Type **`cmd.exe`** into the box.

![Run Dialog With cmd.exe Text In It](https://user-images.githubusercontent.com/66115754/134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2.png)

3. Press these keys on your keyboard to open it as Administrator:  
   `Ctrl + Shift + Enter`

![Run as Administrator Prompt](https://user-images.githubusercontent.com/66115754/134801445-9b90e121-350b-42ea-afec-b499f1fbfae9.png)

4. Click **Yes** on the prompt that appears.

![Command Prompt Window](https://user-images.githubusercontent.com/66115754/134807479-53ccdaf9-feb0-49a3-9843-5bb4db016128.png)

---

### The commands
Now, type the following command:
```cmd
slmgr.vbs /upk
```
Now it will give an message, click on OK.

And now this command:
```cmd
slmgr.vbs /cpky
```
It will give an message once again, and click on OK again.

And now type this command:
```cmd
slmgr.vbs /ckms
```
Once again click on OK when you get an message.

### Edition upgradable check command
Now we are gonna check of your edition is supported to upgrade to Pro, run the following command to check this:
```cmd
DISM /online /Get-TargetEditions
```
If you see "Professional" in the list, then you can upgrade your Windows edition to Pro for free!

### Running Windows Pro installer
Now, copy and paste this complete command:
```cmd
sc config LicenseManager start= auto & net start LicenseManager
```
```cmd
sc config wuauserv start= auto & net start wuauserv
```
```cmd
changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T
```
```cmd
exit
```

It will run an installer and you will see an message:"% complete"

Now wait until it's 100% and it's not weird that you will get an error.

When you get the error, just click Exit and then reboot your pc.

You will now see an message that he is running updates and is installing features, just wait until its done and check "info" in settings, You will see that Windows 11 Pro is installed! 

But we are not done, You will see that it isn't activated and that you can't change some settings, now we are gonna fix that!

## Activating Windows Pro
Now we are gonna run some other commands to activate Windows 11 Pro.

Press these keyboard keys once again:

`Windows-logo key + R`

It looks like this again:

![Run Dialog With cmd.exe Text In It](https://user-images.githubusercontent.com/66115754/134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2.png)

Press `ctrl + shift + enter`

You will get an message, just click on Yes.

Now you will get an Command Prompt.

Type the following commands one for one to activate:

```cmd
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
```

```cmd
slmgr /skms kms8.msguides.com
```

```cmd
slmgr /ato
```
 
Now you have Windows 11 Pro and it activated! You can check settings to see it.


# Last Words
I hope you enjoy it!
If you have any further questions, you can email me at "mendisdanushka886@gmail.com" or comment on this guide.
