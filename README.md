# Youkilds
Youkilds is script for disable Youtube ads. So... you can enjoy watching without seeing ads.

## Installation
**OpenWRT** 
- First, you must install lib **Simple-Adblock** (include dnscrypt-full). If you don't have, you can install from Stangri repo [**Here**](https://stangri.github.io/openwrt-repo/)
- After you installed simple-adblock, login to you router IP
- Go to service menu, click simple-Adblock
- Click + icon on Blacklist Hosts, and add my host to blank form [like here](https://i.imgur.com/rougyUJ.png)
- Save and apply.
        
        if you got problem when downloading or merge host, click reload till simple-adblock running(enable). Or you can delete few hosts listed on Blacklist Hosts

**Android Rooted (including Set Up Box)**
- Open ES File Manager or Root Explorer
- Navigate to /system/etc
- Locate and long-press the hosts file
- Tap the menu button
- Select Properties
- Tap Change in the Permissions section
- Copy my hosts file and paste(merge) on original hosts in /system/etc (you can add another host for powerfull blocking ads.)
- Tap the check box for Group under the Write column [like this](https://tr1.cbsistatic.com/hub/i/r/2014/09/30/f26f8035-bf67-494a-b9b8-3f4cebfdf475/resize/770x/feb6f836035f60d4eb46849af498e5e9/hosts2.png)
- Tap OK
- Tap Cancel
- Reboot device

### Thanks to:
https://www.techrepublic.com for tutorial change hosts file on Android
