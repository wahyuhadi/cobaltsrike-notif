# Red Team Architecture

![cobalstrike](https://www.cobaltstrike.com/images/pivotgraph.png) 


### Telegram Baecon Notif

* change chat_id and  telegram token in telegram.py

		chat_id = 'xxx' #userID

		bot = telepot.Bot('xxxxxxxx') #token telegram


* change location telegram.py in script .cna

	    $cmd = '/home/rwx/tools/aggregessor/notif/telegram.py --computername ' . $computerName . " --internalip " . $internalIP . " --username " . $userName;
	       
	      
	 
* Initial Beacon 
![notif](./image/text2.png)

* Aggressor log example

![notif](image/text1.png)

* Telegram Notif Example

		Message from archlinux Server
		Beacon succes implant Info Target
		Username : user
		Ipaddres : 192.168.56.101
		Computer name : USER-PC.
&copy; [Rahmat Wahyu Hadi](https://github.com/wahyuhadi) - 2019

