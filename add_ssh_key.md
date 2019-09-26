Add ssh key to github.
1. Check if any ssh keys exist already. Run 'ls -al ~/.ssh'
2. If not, generate one. Run 'ssh-keygen -t rsa -b 4096 -C "your_email@example.com"'. Press enter til end.
3. Install xclip. Run 'sudo apt-get install xclip'. This just automatic copy the result of terminal for you.
4. Run 'xclip -sel clip < ~/.ssh/id_rsa.pub' to copy the key.
5. Go to github website and paste the key to the settings.