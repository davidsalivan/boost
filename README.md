# boost
In this repository are original unchanged [BOOST](http://www.boost.org/) sources. We keep for now only latest package used by [ion core CE](https://github.com/cevap/ion/) as well as all following from now on. 

[Download latest Boost version](https://sourceforge.net/projects/boost/files/latest/download?source=files) from sourceforge.
## original Boost downlaod links

Links and ressources
--------------------

[original Boost releases](https://dl.bintray.com/boostorg/release/) - [Original Boost binaries](https://dl.bintray.com/boostorg/release/boost-binaries/)

 - [v1.64.0](https://dl.bintray.com/boostorg/release/1.64.0/source/)
 ```
wget https://dl.bintray.com/boostorg/release/1.64.0/source/boost_1_64_0.tar.bz2
 ```
 - [v1.63.0](https://dl.bintray.com/boostorg/release/1.63.0/source/)
 ```
 wget https://dl.bintray.com/boostorg/release/1.64.0/source/boost_1_64_0.tar.bz2
 ```

Build Boost
-----------

If you need to build Boost yourself:

	sudo su
	./bootstrap.sh
	./bjam install