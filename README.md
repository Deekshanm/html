ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

eval "$(ssh-agent -s)"

ssh-agent cmd

ssh-add %USERPROFILE%\.ssh\id_rsa

type %USERPROFILE%\.ssh\id_rsa.pub | clip

ssh -T git@github.com(to check)

