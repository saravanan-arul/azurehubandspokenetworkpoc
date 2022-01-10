# azurehubandspokenetworkpoc

Purpose: A proof of concept of a hub and spoke azure network architecture with a site to site vpn to a simulated onpremises network. For training and educational purposes.

You may be engineering an azure network that supports the following
1. Adopt a hub and spoke architecture
2. The hub virtual network serves to host the virtual network gateway, domain controller, DNS server and any other shared services infrastructure. 
3. The spoke networks such as a prod VNet and a dev vnet support respective production and dev workload environment.
4. The on premises VNet is to emulate an onpremises network and use its VNET gateway as the VPN device to establish an hybrid cloud network connection in the form of a Site to Site VPN connection between the VNET Gateways. 


