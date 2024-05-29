
### Installing Cloak 2 Plugin
Copy and execute this command as root user:
```bash
sudo su -
bash Cloak2-Installer.sh
```


### Get information of cloak server:
```bash
root@ip-172-31-32-206:/etc# cd cloak/
root@ip-172-31-32-206:/etc/cloak# cat shadowsocks.json
{
        "Public IP":"",
        "Password":"in6KHWwEHZtJmUQS",
        "Port":"443",
        "Encryption":"chacha20-ietf-poly1305",
        "Cloak Proxy Method":"shadowsocks",
        "ProxyMethod":"shadowsocks",
        "EncryptionMethod":"plain",
        "UID":"coQXCiVUFSUCFk+I1AQQKw==",
        "PublicKey":"f7aLMAwrw3tVXMZGjqTC3DbW1U4fg/vIeCBy0bWhDUM=",
        "ServerName":"204.79.197.200:443",
        "NumConn":4,
        "BrowserSig":"chrome",
        "StreamTimeout": 300
}

```

### Check IP Public
```bash
curl http://checkip.amazonaws.com
```
