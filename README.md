# Find-Wi-fi-Passwords-using-Python

# Introduction :
This article will show you how you can find wifi passwords using python. if you forget your wifi password so this python script can find your wifi password. To find the already connected wifi passwords we need to execute two commands on the terminal so in this program we’re running these two commands using the python script. 

# Note: this python script shows wifi passwords only for that wifi network that was connected early to the system. this script can’t find wifi passwords for the unknown wifi network or other nearby wifi networks.

# Explanation:
To find the wifi passwords we need to run two commands on the terminal so to run commands using python scripts we need to import the python subprocess module. subprocess module allows you to spawn a new process. 

The two below commands are used to check the wifi passwords

$ netsh wlan show profile
$ netsh wlan show profile PROFILE-NAME key=clear
the first command is used to find wifi the profiles of the connected wifi networks and the second command is used to display the password of the wifi network.

# Output:
The wifi name and its passwords are displayed.
