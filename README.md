wget https://github.com/Lolliedieb/lolMiner-releases/releases/download/1.29/lolMiner_v1.29_Lin64.tar.gz

tar -xf lolMiner_v1.29_Lin64.tar.gz

cd 1.29

./lolMiner --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUbXKYJBTYgRDXppuWxHMF7dTaPwXWZHPf.Splash_LK#ek61-6h9x --ethstratum ETHPROXY  


./lolMiner --algo ETHASH --pool ethash.unmineable.com:3333 --user TRX:TUbXKYJBTYgRDXppuWxHMF7dTaPwXWZHPf.Splash_LK#ek61-6h9x --ethstratum ETHPROXY  


#!/bin/bash
POOL=ethash.unmineable.com:3333
WALLET=TRX:TUbXKYJBTYgRDXppuWxHMF7dTaPwXWZHPf
WORKEER=$(echo $(shuf -i 1000-9999 -n 1)-USER1#ek61-6h9x)


./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKEER --ethstratum ETHPROXY
     
