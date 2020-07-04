# Setting up SSH Keys

Go to terminal and type the following command (Mac, Linux) replace with your email id.

ssh-keygen -t rsa -C "you@email.com"

Copy the generated key using following command starting from word ssh.

cat ~/.ssh/id_rsa.pub

Paste it in github, bitbucket or gitlab respective of your remote.
Save it.
