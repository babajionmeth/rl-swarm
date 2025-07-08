```bash 
sed -i -E 's/(startup_timeout: *float *= *)[0-9.]+/\1120/' $(python3 -c "import hivemind.p2p.p2p_daemon as m; print(m.__file__)")
```
```bash 
git clone 



