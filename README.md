
nodeviz – A fast and small Bitcoin node visualition tool
=============================================================

<img src="https://github.com/victorsintnicolaas/bitcoin-node-visualizer/blob/master/Example.jpg?raw=true" width="550">

##### Dependencies:
	curl
	leveldb
	boost_system
	boost_thread
	boost_chrono
	cxxopts (header-only included)
	catch test framework (header-only included)
	PicoSHA2 (header-only included)

##### Building steps:
	clone this repository
	clone leveldb into nodeviz/lib
	make all

##### get ip addresses
	./nodeviz --init
	./nodeviz

##### get longitude and latitude
	./nodeviz --collectip
