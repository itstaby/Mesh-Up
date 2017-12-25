# Mesh-Up
Mesh Up is an Android application that aims to establish a multi-hop communication network in the absence of usual network connectivity.

The motivation lies in creating communication possibilities with smartphones in areas where there is no reception of regular cellular service or internet connectivity.

It establishes distributed, multi-hop meshes of local networks, that are inter-connected by shared peers.
Wi-Fi Hotspots are used to create local networks with one node acting as a server.

Any peer that is in the vicinity of two potential servers acts as a bridge between two the networks in which all devices may not be in range, thus the multi-hop nature of the application, with messages routed between multiple smaller networks, extending reachability to out-of-reach devices.

Each device connects to the nearest server, and informs the server of all other hotspots in its vicinity to which it can act as a bridge.
If no server is found, the device assumes the role of a server for other upcoming devices.

The distributed applciation handles message transfer and contingencies for handling dead or vanishing servers, and other possible problems of a distibuted network.
