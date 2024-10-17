# How to access website in termux from PC just by connect via cable:
`adb forward tcp:18080 tcp:8080` and then access localhost:18080

# How to undo port forward:
`adb forward --list`  
`adb forward --remove tcp:<local_port>`  
`adb forward --remove-all`  
