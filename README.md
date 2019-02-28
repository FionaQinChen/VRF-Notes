# VRF-Notes
Some information about vrf for my study

[VRF Configuration]
The following example shows two VRF devices configured on top of the switch ports:

            +------------------------+                   +------------------------+
            |  vrf-blue (table 10)   |                   |   vrf-red (table 20)   |
            +------------------------+                   +------------------------+
               |                  |                         |                  |
           +-------+          +-------+                 +-------+          +-------+
           | sw1p3 |          | sw1p5 |                 | sw1p4 |          | sw1p6 |
           +-------+          +-------+                 +-------+          +-------+
         192.168.100.1/24   192.168.101.1/24          192.168.100.1/24   192.168.200.1/24
To create the VRF devices on switch 5812-3.1 version, run:

