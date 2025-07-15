# Download the files 
```bash 
git clone https://github.com/babajionmeth/rl-swarm && cd rl-swarm && chmod +x run_rl_swarm.sh
```
# Download the dependencies 
```bash 
sudo apt update
sudo apt install -y build-essential python3-dev
```
```bash 
curl -sSL https://raw.githubusercontent.com/zunxbt/installation/main/node.sh | bash
```
```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip curl screen git yarn && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```

# Run with this command 
```bash 
python3 -m venv .venv && source .venv/bin/activate && ./run_rl_swarm.sh
```










