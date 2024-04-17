# SSH Key Steps
### 1. Generate key pair in desired folder using `ssh-keygen -t rsa -b 4096 -C "enter your email here"`.<br>
It can be advised to have a folder exclusively for SSH keys, this folder can also be hidden. You will need to name your key, and you can give it a passphrase if you would like to.<br>
![img.png](images%2Fimg.png)<br>


### 2. Use the `cat` command to get contents of the **.pub key**.<br>
![img_1.png](images%2Fimg_1.png)<br>


### 3. Copy to Github and deploy keys. **Include write option**.<br>
![img_3.png](images%2Fimg_3.png)<br>![img_4.png](images%2Fimg_4.png)<br>![img_9.png](images%2Fimg_9.png)<br>![img_10.png](images%2Fimg_10.png)
### 4. Go to repo in Git Bash and execute ```eval `ssh-agent` ```command. <br>
![img_11.png](images%2Fimg_11.png)<br>
### 5. Use the `ssh-add "path to ssh key folder"` command.<br>
![img_12.png](images%2Fimg_12.png)<br> 
### 6. Use `ssh -T git@github.com` to test the connection. <br>
I included my mistake in this screenshot
![img_13.png](images%2Fimg_13.png)<br>
