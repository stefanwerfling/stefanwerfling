1. Createn OpenVPN
2. Load on mobile the app OpenVPN Connection
3. Upload your config over anydesk or other remote software
4. Start Wlan Debugging and check the listen ip
4.1 When the Listen is not on the VPN IP, then start a portforwarding app, e.g. my app: https://github.com/stefanwerfling/apf
5. go /home/~/Android/Sdk/platform-tools and start a shell for linux
6. ./adb pair vpn ip":"listen port"
   - you will ask for the code
7. ./adb connect "vpn ip":"listen port"
  
  Now you see the device in your ide.
