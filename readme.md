ls -al ~/.ssh

ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa


ssh -T git@github.com
