# MULTIPORT VPN V2023

<p align="center">
  <img src="https://raw.githubusercontent.com/anzclan/MULTIPORT2023/main/ss.png" />
</p>

## TESTED VPS
     * DIGITALOCEAN (DEBIAN 10/11)
     * AWS (DEBIAN 10 / UBUNTU - SSH WS NOT WORKING ON UBUNTU)
     * OVH (DEBIAN 10/11) (REQ root Akses)
     * IDCLOUDHOST (REQ root Akses)
     
### RECOMMENDATION OS
     * DEBIAN 10

## YOU CAN USE THIS TO GET ROOT AKSES
<pre></code>sudo su
wget https://raw.githubusercontent.com/anzclan/ovh-root/main/root && bash root</code></pre>

## PORT INFO
     - Open SSH                : 443, 80, 22        
     - Dropbear                : 443, 109, 143      
     - Dropbear Websocket      : 443, 109           
     - SSH Websocket SSL       : 443                
     - SSH Websocket           : 80                 
     - OpenVPN SSL             : 443                
     - OpenVPN Websocket SSL   : 443                
     - OpenVPN TCP             : 443, 1194          
     - OpenVPN UDP             : 2200               
     - Nginx Webserver         : 443, 80, 81        
     - Proxy Loadbalancer      : 443, 80            
     - DNS Server              : 443, 53,           
     - DNS Client              : 443, 88            
     - OpenVPN Websocket SSL   : 443                
     - XRAY DNS (SLOWDNS)      : 443, 53            
     - XRAY Vmess TLS          : 443                
     - XRAY Vmess gRPC         : 443                
     - XRAY Vmess None TLS     : 80                 
     - XRAY Vless TLS          : 443                
     - XRAY Vless gRPC         : 443                
     - XRAY Vless None TLS     : 80                 
     - Trojan gRPC             : 443                
     - Trojan WS               : 443                
     - Shadowsocks WS          : 443                
     - BadVPN 1                : 7100               
     - BadVPN 2                : 7200               
     - BadVPN 3                : 7300               
     - Proxy Squid             : 3128 & 8000
     
### INSTALATION
<pre><code>apt update && apt upgrade -y && apt install curl -y && apt install -y wget screen && wget https://raw.githubusercontent.com/anzclan/MULTIPORT2023/main/install.sh && chmod +x install.sh && ./install.sh</code></pre>

### INSTALL KEY -- > https://t.me/dotycat/427

## VERSION
V1.6.1 - 16/02/2023

## INCOMPLET
   - SOCKS (ceck user, View User config, Renew Users , etc)
   
## BUY ME A COFFEE (Donate:)
<p align="center"><img src="https://raw.githubusercontent.com/anzclan/MULTIPORT2023/main/ss.jpg" width="280" height="400"></p>
<p>
