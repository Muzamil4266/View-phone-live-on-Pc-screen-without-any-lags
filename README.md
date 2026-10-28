# View-phone-live-on-Pc-screen-without-any-lags
You can view your phone live on PC screen with scrcpy without any lag and it works brillantly personally tested
🔴How to view phone display on laptop without lags best process 

Note that although apps exist which lets you view phone on laptop or pc but they lag so much but here we have a method which works brilliantly in viewing phone screen on laptop without any lag or delay and without any 3rd party app hassle all you need to do is install scrcpy exe on your pc from GitHub 


Then check if scrcpy is installed by typing scrcpy --version in cmd if it was installed on your pc then it shows like this 

PS C:\Users\khano> scrcpy --version
scrcpy 4.0 <https://github.com/Genymobile/scrcpy>

Dependencies (compiled / linked):
 - SDL: 3.4.8 / 3.4.8
 - libavcodec: 62.28.101 / 62.28.101
 - libavformat: 62.12.101 / 62.12.101
 - libavutil: 60.26.101 / 60.26.101
 - libusb: - / 1.0.29




If it is not installed then you install it take ai help if you needed any or stuck any error


Then turn on usb debugging 



Then connect phone to pc by usb



Then turn on file transfer option from popup



Then allow any permissions on phone 



Then type scrcpy in cmd command and your phone instantly gets viewed on laptop whatever you do on your phone gets on laptop and it doesn't needed any python code or script anything instead it needs only cmd and you are done



Then you do any Amazing thing by it like some of these are




Viewing your ears inside 


Viewing back of head



Viewing any body part that you unable to view with only phone 




Viewing pcb on laptop while doing soldering work 




Attaching tiny camera on phone that goes deep inside your mouth and you view it on your pc screen 



Etc etc many amazing things 


Note you can also view landscape mode so that the live feed covers full pc widescreen area you just turn your phone into landscape mode


And all process is personally verified it works brilliantly






⭐⭐⭐WIRELESS METGOD PERSINALLY TESTED WORKS BRIILANTLY WITHOUT ANY LAGS JUST LIKE USB METHIOD


Here is your complete, lag-free guide to running **scrcpy** wirelessly just like a USB cable. Save this guide for quick reference!

---

### Wireless Scrcpy Connection Guide

#### Step 1: Initial Setup (Required only once with a USB cable)

1. **Connect your phone to your laptop** using a USB cable.
2. Open **Command Prompt (cmd)** or **PowerShell** on your laptop.
3. Type the following command and press Enter to switch ADB to network mode:
```cmd
adb tcpip 5555

```


*(You should see a message saying: `restarting in TCP mode port: 5555`)*


4. **Unplug the USB cable** from your phone.



---

#### Step 2: Find Your Phone's IP Address

1. Go to your phone's **Settings** > **Wi-Fi**.
2. Tap on your connected Wi-Fi network name to view details.
3. Look for your phone's **IP Address** (it usually starts with `192.168...` or `100...`).

---

#### Step 3: Connect Wirelessly & Run Scrcpy

1. Ensure your laptop and phone are connected to the **same Wi-Fi network**.
2. In your laptop's Command Prompt, connect to your phone using its IP address:
```cmd
adb connect <your-phone-ip>:5555

```


*(Example: `adb connect 100.73.148.192:5555`)*
3. Once it says **"connected to..."**, simply type:
```cmd
scrcpy

```



Your phone screen will instantly pop up on your laptop with zero lag, exactly like using a physical USB lead!

---

### Quick Future Reconnection

Whenever you want to use it again later, just ensure Wi-Fi is on, open CMD, type `adb connect <your-phone-ip>:5555`, and then run `scrcpy`.
