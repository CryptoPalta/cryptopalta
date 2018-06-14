# cryptopalta
CryptoPalta, basado en CryptoNote (Bytecoin). Apoyanos
###Instalación en Linux###


$ apt-get update
$ apt-get upgrade
$ apt-get install qtbase5-dev libssl-dev cmake git libboost1.58-all-dev build-essential g++
$ git clone https://github.com/CryptoPalta/cryptopalta
$ cd cryptopalta/
$ cmake CMakeLists.txt
$ make -j 8
$ cd cryptonote/
$ make -j 8

Recuerda anteponer el comando "sudo" antes de cada comando
