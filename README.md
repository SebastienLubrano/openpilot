Installation may or may not compile if installed directly via the URL on the device.   
  
SSH Install on the Comma Three:  
`cd /data; cp -rf ./openpilot ./openpilot.bak; rm -rf ./openpilot; git clone --recursive --branch 0.8.8-shane-spektor-coasting https://github.com/SebastienLubrano/openpilot.git; sudo reboot`  
  
SSH Install on the Comma Two:  
`cd /data; cp -rf ./openpilot ./openpilot.bak; rm -rf ./openpilot; git clone --recursive --branch 0.8.8-shane-spektor-coasting https://github.com/SebastienLubrano/openpilot.git; reboot`  
  
If you already installed but it fails to compile (Comma Three):   
`git submodule update --init --recursive && sudo reboot`   
  
If you already installed but it fails to compile (Comma Two):   
`git submodule update --init --recursive && reboot`  
