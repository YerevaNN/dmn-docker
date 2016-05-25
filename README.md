# dmn-docker
Dockerfile for starting DMN with UI

Usage
-----

This image contains [DMN](https://github.com/YerevaNN/Dynamic-memory-networks-in-Theano) and UI for it. 

To get this image do:
```bash
$ docker pull yerevann/dmn
```

To run this image do:
```bash
$ docker run --name dmn_1 -it --rm -p 5000:5000 yerevann/dmn
```

It will start a server on the 5000 port. The first prediction will take some time, because the model should be loaded into memory. Just wait a bit until it returns the result. The following predictions will be fast.