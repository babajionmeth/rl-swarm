```bash 
sed -i -E 's/(startup_timeout: *float *= *)[0-9.]+/\1120/' $(python3 -c "import hivemind.p2p.p2p_daemon as m; print(m.__file__)")
```
```bash 
git clone https://github.com/babajionmeth/rl-swarm && cd rl-swarm && chmod +x run_rl_swarm.sh
```




```bash 
python3 -m venv .venv && source .venv/bin/activate && ./run_rl_swarm.sh
```




