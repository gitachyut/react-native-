##Physical device (easier)

Port proxy for physical device (-d will automatically target physical device)  
`adb -d reverse tcp:8081 tcp:8081`  
  
Start ADB server  
`adb start-server`   
  
Run react-native server for hot reloading  
`react-native start`    
  
Start Android app on the physical device  
`react-native run-android (~30sec)`    
  
Shake the device and enable Hot reloading and Live Reload (useful the first time)  
