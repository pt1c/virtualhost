# Virtualhost (Apache2 + Nginx) Manage Script
Shell Script to allow create or delete apache and nginx virtual hosts on Debian on a quick way.

You need Apache2 and Nginx both installed.

## Installation ##
	# cd /usr/local/bin
	# wget -O anvh https://raw.githubusercontent.com/pt1c/virtualhost/master/anvh
	# chmod +x anvh
  
## Usage ##
	# anvh [create | delete] [domain]

## Example ##
create:

	# anvh create test.com
	# anvh create dev.test.com
	
delete:

	# anvh delete test.com
	# anvh delete dev.test.com
