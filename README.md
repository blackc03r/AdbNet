# AdbNet ![image](https://user-images.githubusercontent.com/86132648/124664774-ec316000-de79-11eb-8fbe-254bf466d2ba.png)
A Framework that allows you to search for vulnerable android devices across the world and exploit them.

# Features
AdbNet is a framework that makes your life easier when trying to hack android devices. It has tons of features.

```
Features:
  - Post-Exploitation modules to control and tinker with the device you are connected to.
  - Scanners to search for vulnerable android devices across the world to exploit.
  - Options for managing how many devices you have connected.
  - Options for checking whether the devices you are connected to are online or offline.
  - IP-Lookup for retrieving information on a certain IP.
  - Options to dump the IP Addresses of the vulnerable android devices. [This makes your life easier so you dont have to find it yourself]
```

# Getting the required API keys
Create an account on censys.io and then go to your account page and get your free api_id and api_secret key and open 'adbnet.py' and edit in your api id and api key here: 

![image](https://user-images.githubusercontent.com/86132648/124665489-c6588b00-de7a-11eb-984b-b9e3118aba81.png)

Create an account on shodan.io and go to your account to get your free api key, once you have it copied, open 'adbnet.py' and edit in your api key here:
![image](https://user-images.githubusercontent.com/86132648/124665543-d7090100-de7a-11eb-9ef6-e400227a1359.png)

# Simple Tutorial
This tutorial is for people that might be confused on how to use AdbNet. This tutorial will demonstrate how to connect to a vulnerable device and run some post-exploitation modules on it, or just open a regular shell.
```
First, run the 'dump shodan' command to dump the IP addresses of the vulnerable devices.

Then, after you find an IP-address you want to try, run the 'connect' command and you will be prompted to enter
the target IP address, once you enter the target ip address, you will be prompter to enter the port. For the port,
you can try entering '5555' or '4444' since those are the most common ports. If you want, you can try finding the
specific port yourself, but it might take some time.


```

# Installation/How To Run
```
sudo apt install pq
sudo apt install adb
pip3 install colorama
pip3 install requests
python3 adbnet.py or python adbnet.py or py adbnet.py

TIP: For people that are new to this, if you are having issues install a certain python module, just do this: pip3 install <modulename>
```
# Screenshots
![image](https://user-images.githubusercontent.com/86132648/124667060-e2f5c280-de7c-11eb-8f69-2443aa7a7bd3.png)
![image](https://user-images.githubusercontent.com/86132648/124667104-f30da200-de7c-11eb-9da3-098fa211a910.png)

# Credits
  - @0x1CA3 on Github
