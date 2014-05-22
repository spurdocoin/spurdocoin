Spurdocoin
================================
Pakko mainaa.

Tavoitteena pelastaa lautakulttuuri lopullisesti.

Specs
----------------
P2P port: 10070

RPC port: 21070

Coin reward per block: 609

100% PoW: X11

Difficult readjustment: every 120 blocks

Block generation: 5 min

Viljamin veljen vinkit debian käännöksiin
-------

    sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.1-dev libdb5.1++-dev qt-sdk
    
    qmake -qt=qt4 bitcoin-qt.pro "USE_UPNP=-"
    
    make
