# Wifi-Password-with-python

We will use the subprocess module of Python which makes it easy to check the connected wifi passwords by allowing us to run (cmd)command prompt commands inside our program.

Logic is very simple, we will run cmd commands to check wifi passwords inside our program with the help of the subprocess module as mentioned above.

There are two cmd commands basically to check connected wifi passwords

netsh wlan show profile
netsh wlan show profile PROFILE-NAME key=clear
The first command is used to show the profiles of the connected wifi while 2nd is used to show the password of the wifi which you want to know.

Here we will use these two commands in our own way to Get WiFi Passwords With Python.
