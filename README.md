# raspindiGUISetup
setup tool using ansible to make a raspberry pi ready automatically for streaming

on a new raspberry pi, run these steps:

```
sudo apt-get install ansible
cd ~/Desktop
git clone https://github.com/TIU11/raspindiGUISetup.git
cd raspindiGUISetup/
ansible-playbook raspindi_playbook.yml
```
ths will install and update all dependencys then restart your pi, 
after restart your pi should automatically open up the py script that was auto cloned from
https://github.com/TIU11/raspindiGUI. If this didnt work for you, then follow the steps manually from 
https://github.com/raspberry-pi-camera/raspindi and install my py script

