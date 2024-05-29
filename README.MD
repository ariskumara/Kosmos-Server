
### Installing Cloak 2 Plugin
Copy and execute this command as root user:
```bash
sudo su -
bash Cloak2-Installer.sh
```

### Installing Cloak 2 Plugin
Get information of cloak server:
cd /etc/cloak
/etc/cloak# ls
ckadminclient.json  ckport.txt  ckserver.json  shadowsocks.json  userinfo.db

root@ip-172-31-36-180:/etc/cloak# cat ckadminclient.json
{
        "ProxyMethod":"panel",
        "EncryptionMethod":"plain",
        "UID":"gzZkDqFTJXy2VUUd0qwq9g==",
        "PublicKey":"cEbS8IXl/fF7ZrTjE3Dh4mZ5iTGBQ7RUEEcQ461kaQY=",
        "ServerName":"www.bing.com",
        "NumConn":1,
        "BrowserSig":"chrome",
        "StreamTimeout": 300
}
root@ip-172-31-36-180:/etc/cloak# cat shadowsocks.json
{
        "ProxyMethod":"shadowsocks",
        "EncryptionMethod":"plain",
        "UID":"iKEnUSpRROW3h5vv8krCtQ==",
        "PublicKey":"cEbS8IXl/fF7ZrTjE3Dh4mZ5iTGBQ7RUEEcQ461kaQY=",
        "ServerName":"204.79.197.200:443",
        "NumConn":4,
        "BrowserSig":"chrome",
        "StreamTimeout": 300
}

### Check IP Public
curl http://checkip.amazonaws.com
