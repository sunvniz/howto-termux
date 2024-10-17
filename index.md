# How to SSH from PC to Termux without wifi or internet, just by connect via cable
1. Forward port 8022 to android device port 8022 `adb forward tcp:8022 tcp:8022`
2. SSH `ssh -p 8022 localhost`
3. done
