# BitcoinServerSetup

How setup bitcoind in ubuntu/linux system.

Download link https://bitcoin.org/en/download

Extract bitcoin-0.15.0.1-x86_64-linux-gnu.tar.gz

Using tar -xvf bitcoin-0.15.0.1-x86_64-linux-gnu.tar.gz

Result……………………………………..
bitcoin-0.15.0/
bitcoin-0.15.0/bin/
bitcoin-0.15.0/bin/bitcoin-cli
bitcoin-0.15.0/bin/bitcoind
bitcoin-0.15.0/bin/bitcoin-qt
bitcoin-0.15.0/bin/bitcoin-tx
bitcoin-0.15.0/bin/test_bitcoin
bitcoin-0.15.0/include/
bitcoin-0.15.0/include/bitcoinconsensus.h
bitcoin-0.15.0/lib/
bitcoin-0.15.0/lib/libbitcoinconsensus.so
bitcoin-0.15.0/lib/libbitcoinconsensus.so.0
bitcoin-0.15.0/lib/libbitcoinconsensus.so.0.0.0
bitcoin-0.15.0/share/
bitcoin-0.15.0/share/man/
bitcoin-0.15.0/share/man/man1/
bitcoin-0.15.0/share/man/man1/bitcoin-cli.1
bitcoin-0.15.0/share/man/man1/bitcoind.1
bitcoin-0.15.0/share/man/man1/bitcoin-qt.1
bitcoin-0.15.0/share/man/man1/bitcoin-tx.1

cd bitcoin-0.15.0/bin/

Now  run  ./bitcoind -deamon

Result :: Bitcoin server starting

Go go home folder cd ~

See hidden folder using ls -a

Now You see  .bitcoin folder Enter into that using cd .bitcoin

Create new file :: touch bitcoin.conf. 

Paste in bitcoin.conf file

server=1
testnet=1
rpcuser=rpcuserrpc
password=somesecretpassword

Set Path to bitcoin-0.15.0/bin/  or You enter in bitcoin-0.15.0/bin/ folder and then run command 

./bitcoin-cli getbalance return balance







