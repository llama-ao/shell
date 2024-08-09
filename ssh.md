## copy file to remote server
ssh vps "mkdir -p ~/.ssh"   
scp ~/.ssh/contabo_rsa.pub vps:~/.ssh/authorized_keys 
