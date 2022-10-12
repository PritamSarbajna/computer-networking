# Old Design of Data Center :

- Mainly based on north south traffic.
- To reach a server, how many hop a packet will require wasn't predictable.
- It used to take a lot of time to reach a packet from server to server.
- It would not be able to handle east west traffic.

### Diagram :

![1](https://user-images.githubusercontent.com/90236635/195327194-cb32e1ff-a615-4b66-81b3-eb753dfc969f.jpg)


# New Design of Data Center :

- Also known as **spine-leaf design**.
- It actually uses massive switches which are in distribution layer. (eg. Cisco nexus class switches)
- The distribution layer switches are known as **_spine nodes_**.
- The access layer switches are known as **_leaf nodes_**.
- It's now predictible how many hop a packet will take.
- Takes less time to reach a packet from server to server.
- Too many Fiber-optic cables.
- Handles north south traffic as well as east west traffic.

### Diagram :

![2_page-0001](https://user-images.githubusercontent.com/90236635/195332628-98cb285e-2e80-43d0-8da7-cd1704c02d06.jpg)
