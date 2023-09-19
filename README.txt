Image name					Description
systemd-tzdata-image.wic		This image include systemd and tzdata that includes universal 
					timezone and enable us to set default timezone from 
					conf/local.conf file. 


systemd-tzdata-script-image.wic         This image include systemd, tzdata and recipe to add script 
					to target in /etc/init.d folder. That make the script availbale 
					on target for anyone to be able to run it on target.


systemd-startup-service-image.wic       This image include systemd, tzdata, recipe to install script on
					target and create a systemd service to run on target at startup.
					The recipe also enable the service to run at startup. The service 
					install two gpio packages (rgpio and gpiozero), thus, make the 
					packages available to use on target for embedded python.

Link to images: https://drive.google.com/drive/folders/1BZgUYWZbpEEfdXg1feI8CKoZ9SZ_1TNR?usp=drive_link
