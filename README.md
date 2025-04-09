# Gensyn-Testnet-Node-Guide
🚀Credit: Gensyn Node Guide is created by ZUN, I have adjusted Acc to own style so that my community can easily join the Gensyn testnet.

Join Telegram https://t.me/testnetmaterial

## Install Packages

### 1. Update System Packages
```bash
sudo apt-get update && sudo apt-get upgrade -y
```

### 2. Install Node.js and npm
```bash
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
```
### 3. Install other file
```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl screen git yarn && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```
### 4. Clone the repo
```bash
rm -rf rl-swarm && git clone https://github.com/zunxbt/rl-swarm.git && cd rl-swarm
```
### 5. (OPTIONAL to force-delete the folder ) 
```bash
sudo rm -rf rl-swarm
```
### 6. Create a screen
```bash
screen -S gensyn
```
### 7. Finally Run 
```bash
python3 -m venv .venv && source .venv/bin/activate && ./run_rl_swarm.sh
```
