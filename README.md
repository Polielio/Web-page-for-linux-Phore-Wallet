# Web page for Linux Phore Wallet

What is "Web page for Linux Phore Wallet" ?

It create a web page to check your balance and the phore network.


How to install it ?

Required:
- A Web Server
- Python installed
- Phore Wallet installed
- FontAwesome file in the directory where you put the php file (you can get it here http://fontawesome.io/get-started/)

Steps:
1) Place the python file (getphore.py) somewhere for example in /home/python/
2) Create a screen:  screen -S pphore
3) Enter: python getphore.py
4) Exit the screen 
6) Wait 60 sec
7) Go to yourwebsite/p/phore.php



Issues:
- If icons do not appear make sure that line 5 of phore.php match with the directory name of your fontawesome 


