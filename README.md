# Connecting Two Virtual Networks

This is a project that shows my ability to connect resources in two or more separate Virtual Networks. These resources may be
Virtual Machines, Starage Accounts, Azure SQL databases and so many more. To be precise, the project above connects three
Virtual Machines, with one of them being in a different location. The Sandbox virtual machine sends and recieves network traffic,
through the HTTP protocol, from the internet and shares it with the work(same virtual network) and workload(different virtaul network)
virtual machines. It shares this network traffic with the other virtual machines through the SSH protocol.

The project file is accompanied by a visual illustration of how the resources are connected and how they are able to share information.
