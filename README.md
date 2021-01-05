The goal of this project is to build a basic VRF lab.

This lab has been build using the EVE-NG network emulator.

At the end of the configuration we can se that only VPC2 can ping VPC3, as part of the VRF CUST-A and only VPC4 can ping VPC5, as part of the VRF CUST-B.

Both e0/1 and e0/3 ports on ISP router have the 10.1.1.1/24 IP address configured, but they are part of different routing instances(VRFs).