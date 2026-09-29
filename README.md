# Clos_Network_L3_EVPN_Asymmetric_Model


Topology:


<img width="1280" height="440" alt="image" src="https://github.com/user-attachments/assets/6df7d654-6f08-49ac-ad12-a91d4d53b6ee" />



# RFC 9135 - Integrated Routing and Bridging in Ethernet VPN 

Defines two modes of operations for L3 VPN, Symmetric and Asymmetric. SR Linux support both.

In this lab we configure an L3 VPN with asymmetric routing


With an asymmetric L3VPN, we will interconnect fist MAC-VRF "mac-vrf-100" with a second MAC-VRF "mac-vef-200". it initially both MAC-VRF will be independent from each other, providing tenant-isolation.
