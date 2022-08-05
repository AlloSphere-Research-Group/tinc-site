## TINC (The Toolkit for Interactive Computation)

The [Toolkit for Interactive Computation (TINC)](https://github.com/AlloSphere-Research-Group/tinc) provides a set of C++ and python classes to assist in the interactive exploration of large datasets by managing parameter spaces, interactive computation and caching of data.

[TINC](https://github.com/AlloSphere-Research-Group/tinc) allows exposing C++ application controls to the network. This simplifies the development of distributed applications as well as creating applications that can be controlled trhrough python without having the application itself depend on python. A great use case is by interacting with the C++ application through a jupyter notebook.

TINC can also be used standalone in python to assist exploration of complex datasets that are spread out through the filesystem through interactive computation prototyping.

## Documentation

 [C++ API documentation](doc/html/index.html)
 
 [Python API documentation](https://tinc-python.readthedocs.io/en/latest/)

 The cache metadata schema can be found [here](https://github.com/AlloSphere-Research-Group/tinc/blob/main/doc/tinc_cache_schema.json). The network protocol used for client/server communication uses protobuf and is defined [here](https://github.com/AlloSphere-Research-Group/tinc/blob/main/src/tinc_protocol.proto).

 ## Tutorials

The [Python API documentation](https://tinc-python.readthedocs.io/en/latest/) contains a set of introductory tutorials to tinc-python. These tutorials focus on usage of TINC in python without requring a C++ server.

The C++ source tree contains a number of small [examples](https://github.com/AlloSphere-Research-Group/tinc/tree/main/examples) that explore the different functionality of the C++ version of TINC


 ## Example applications

[CASM viewer](https://github.com/AlloSphere-Research-Group/casm_viewer) is a large application written using the TINC toolkit, that can display and annotate CASM datasets. It can also be used as a blank canvas for 3D visualization through python notebooks for desktops and immersive environments. 

