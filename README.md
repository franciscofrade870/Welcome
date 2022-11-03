# Welcome
Installing kali and setting up BurpSuite

## Installing a VM

To install kali you first need a VM. I recommend for a first time VM is using Virtual box. This app is free and just like VMware easy to use. The link below will take you to the site.

 - https://www.virtualbox.org/wiki/Downloads
 
 <img src="Virtual Box.gif" width="600">
 
 Once you have downloaded the lastest version of it Virtualbox make sure to run it just in case that it ran correctly. Next Install the extension pack of ' all platforms'. Once installed run that also and it should automatically install itself to Virtual Box.
 
 <img src="Extension Pack.gif" width="600">


 ## Installing Kali
 
 Now that you have your VM installed next will be installing Kali Linux. This flavor of linux is used for Cyber Security and there is other flavors like Parrot Secuirty, RedHat, etc.. etc.. The link below will lead you to the offical kali website. Before we download anything go to the Microsoft store and search for 7zip manager unoffical, this will be needed to install kali. From here we will install the most current version of Kali for Virtual Box. Once that is installed into your machine, extract the file using 7zip.
 
 <img src="7 zip.gif" width="600">
 

<img src="Kali.gif" width="600">


 - When extracting this be sure to extract it somewhere easy to find, or not you will be looking all over tying to find it.
 * Unfortunately I wasn't able to record the extraction, but just use your imagination. :)
 
  - https://www.kali.org/get-kali/#kali-virtual-machines
 
 Once extracted go to the file and click on the vdi file to open it ( the one with the blue box). Doing this automatically opens up Virtual Box and installs Kali already preconfigured. Once it is installed run Kali to make sure it runs properly. 
 
 <img src=".gif" width="600">
 
 On the laucher which is Virtual Box  turn off the machine or save the state. Go into the settings, on the advance settings under the General tab make sure that the clipboard and Drag 'n' Drop are set to Bidirectional. This means you can transfer settings from your host machine to the guest machine. 
 
 # WARNING!!!!!!!!!!!!!!!
 
 The software you going to install is an actual OS used for hacking. Im assuming everyone here is a whitehat hacker, so if you every plan to use this outside of a testing environment there will be reprocussions. Hopefully I didnt turn you into a super villan or introduce you to your villan arc. 

# YOU BEEN WARN!!!!!!!!!!!!!!

# Burp Suite

Kali come preinstalled with a vast variety of tools at your disposal. One of those key tools is BurpSuite. This tool is a hackers bestfriend. This tool is used for performing secuirty testing for web applications. Throughout our lessons we will be using this tool to do various things.

## Configuration

Now that you have the VM setup we start on configuration. In teams I inlcuded the CA Cert for burp suite using firefox. Drag and drop that file into Kali. Next in firefox you want to install a add on called foxy proxy. This will be used as a listener for the browser and BurpSuite to talk with each other.

