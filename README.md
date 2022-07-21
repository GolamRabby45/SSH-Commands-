# SSH-Commands
sudo apt update
# sudo apt-install openssh-server
systemctl status sshd
to see firewall is open or not 

# sudo ufw status
sudo ufw allow ssh
sudo ufw enable
sudo ufw status
sudo ufw allow 22/tcp 
sudo ufw deny 22/tcp 

server config: /etc/ssh/sshd_config
client config: /etc/ssh/ssh_config
man sshd_config

to connect to a server
ssh root@10.0.1.11
pwd
exit
sudo apt install openssh -server
sudo apt install openssh -client


#ssh keygen
key pairs







