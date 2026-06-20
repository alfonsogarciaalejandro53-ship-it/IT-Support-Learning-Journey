# CIDR means Classless Inter Domain Routing
The number after the slash indicates the number of network bits
# Ex:
- /24=255.255.255.0
- /25=255.255.255.128
- /26=255.255.255.192
- /27=255.255.255.224
- /28=255.255.255.240
- /29=255.255.255.248
- /30=255.255.255.252

  # Formula:
  - Host bits= 32 - CIDR
  - Total Addresses = 2*(Host bits)
  - Usable Hosts = 2*(Host bits) -2
