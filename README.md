# ARMLAB Nao Documentation 

## Weblinks: 


**Turn on:** http://doc.aldebaran.com/2-1/nao/nao-turn-on.html

*Note:* Nao doesn not have Autonomous Life package installed. Therefore certain out-of-box fuctions will not work.

**Turn off:** http://doc.aldebaran.com/2-1/nao/nao-turn-off.html

**Charge Battery:** http://doc.aldebaran.com/2-1/nao/battery-charging.html
 TLDR: Battery only charges efficiently when NAO is switched off. 

**Networking with Nao(Linux)**: 

1) Plug in ethernet directly.

- Create new ethernet connection, "NAOBOT" , set IPv4 Setting -> Method to "Link Local Only"
- Press Nao chest button to find IP Address.
- Ping IP/Enter in Chrome to open weblink. 

*Note:* To use both ethernet and eduroam WiFi, open eduroam IPv4 settings -> Routes ->  check box "Use this connection only for resources on this network". Now you should be able to access internet without breaking connection with Nao.

2) Communicate with Nao over WiFi

- Connect Nao with ethernet cable and bring up the Nao homepage.
- Connect to lab WiFi from Homepage
- Disconnect cable, and attempt to ping Nao

3) Interact with Nao:
- SSH into Nao
- cd into /behaviors and locate python files that decribe some actions.

more examples: http://doc.aldebaran.com/2-1/dev/python/examples.html

*Note*: There are some missing libraries. 

## Nao Information:
 
- Naoqi version: 1.14.5.1
- Choreographe version: 2.4.1
- Body Type :  naoH25
- Nao Version: V3.3
- Head Version :  VERSION_40
- Body Version :  VERSION_40
- build date: 2013-06-26 10:47:23 UTC
- build ID: 507ae225aa614ee686f1a9836527033ee2a45772

Serial Numbers:

- HE S/N: ALDT1008B00003353
- BA S/N: ALDE000039B00003810
- BO S/N: ALDR1008E0003619

## Using Choreographe:



## Python SDK:

Workflow format:
```
home/nao/
	behaviours/ 
		demos/
			demo1.py
			demo2.py
			...
			demoN.py
		python_ws/
			yourcodehere.py
```


 
