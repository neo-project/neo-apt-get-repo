# neo-apt-get-repo
This the official `apt-get` repo for `neo-project`.


## Add the Content Below
In a terminal type:
```bash
wget -qO - https://archive.neo.org/ubuntu/neo-project.pubkey.gpg | sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/neo-project.gpg
echo "deb [arch=amd64] https://archive.neo.org/ubuntu stable main" | sudo tee /etc/apt/sources.list.d/neo-project.list
```