
####memorycoin-python

memorycoin-python is a set of python libraries that allows easy access to the
bitcoin peer-to-peer cryptocurrency client API. 

codebase originally derived from <a href="https://github.com/laanwj/bitcoin-python">@laanwj/bitcoin-python</a>. additionaly some modifications made for the portability of memorycoin.

####installation

```bash
$ [sudo] pip install memorycoin-python
```
or if you like 90s:
```bash
$ [sudo] easy_install memorycoin-python
```

####running the deamon

- run `bitcoind` from the memorycoin source. (src/bitcoind) follow the instructions about rpcuser and password.

example memorycoin.conf

```bash
rpcuser=changeme
rpcpassword=changemechangemechangemechangeme
rpcallowip=*
server=1
bind = 0.0.0.0
rpcport=17772
txindex=1
debugvote=1
```

####api
```python
conn = memorycoinrpc.connect_to_local()
print "Your balance is %f" % (conn.getbalance(),)
```

you can explore other methods over the <a href="http://laanwj.github.io/bitcoin-python/doc/">bitcoin-python documentation.</a>