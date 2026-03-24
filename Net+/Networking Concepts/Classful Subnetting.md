- We do not use a class based format ever sine **1993**, but it is referenced in common conversations about [[Subnets|subnets]].
- Class A  = [[CIDR|CIDR /8]]
- Class B = [[CIDR|CIDR /16]]
- Class C = [[CIDR|CIDR /24]]

- It is instead used as a standard value to understand subnets.
- Quickly abandoned because by following this idea we would run out of subnets quickly.

|      Class       |   Leading Bits   | Network Bits | Remaining Bits | Default Subnet Mask |
| :--------------: | :--------------: | :----------: | :------------: | :-----------------: |
|        A         |   0xxx (0-127)   |      8       |       24       |      255.0.0.0      |
|        B         |  10xx (128-191)  |      16      |       16       |     255.255.0.0     |
|        C         |  110x (192-223)  |      24      |       8        |    255.255.255.0    |
| D<br>(Multicast) |  1110 (224-239)  | Not defined  |  Not defined   |     Not defined     |
| E<br>(Reserved)  | 1111 (240 - 255) | Not defined  |  Not defined   |     Not defined     |



--- 
[[COMPTIA NETWORKING +]]