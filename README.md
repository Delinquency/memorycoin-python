---
memorycoin-python is a set of Python libraries that allows easy access to the
bitcoin peer-to-peer cryptocurrency client API.


####installation

```bash
$ [sudo] pip install memorycoin-python
```
or if you like 90s:
```bash
$ [sudo] easy_install memorycoin-python
```

####usage

- run ```bitcoind`` from the memorycoin source. (src/bitcoind) follow the instructions about rpcuser and password.

example memorycoin.conf

```python
rpcuser=changeme
rpcpassword=changemechangemechangemechangeme

rpcallowip=*
server=1
bind = 0.0.0.0
rpcport=17772
txindex=1
debugvote=1

addnode=180.183.156.250:1968
addnode=76.24.94.154:1968
addnode=62.43.2.239:1968
addnode=82.52.177.81:1968
addnode=84.249.109.128:1968
addnode=78.239.107.25:49568
addnode=90.231.187.171:50251
addnode=70.112.30.253:26959
addnode=74.88.177.35:16511
addnode=54.200.207.220:49260
addnode=193.92.140.209:51570
addnode=95.89.105.134:1968
addnode=79.3.168.143:1968
addnode=91.157.155.98:1968
addnode=78.239.107.25:1968
addnode=87.49.126.92:1968
addnode=94.122.229.201:1968
addnode=94.3.149.107:1968
```
