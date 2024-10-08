
# Evaluate performance of 5G service chains

Here the instructions on to use Python code to evaluate the performance of 5G multi-class service chains. 
A service chain (often known as Service Function Chain - SFC) is a structure made of virtualized nodes to be traversed in a specific order to provide a given service.
This Python code allows to evaluate performance of an SFC-like structure made of 5G core network nodes relying on the Open5GS framework.
The involved nodes are: the Access and Mobility Management Function (AMF) in charge of managing access and moobility, the Session Management Function (SMF) in charge of handling session establishment, and the User Plane Function (UPF) in charge of managing data plane.

From an architectural perspective, we distinguish (see figuire below):
- 5G Mono chain: a 5G chain made of a single path of nodes
- 5G Poly chain: a 5G chain made of multiple paths of nodes

<img src="mono_poly.png" alt="My Image" width="400"/>


Test
