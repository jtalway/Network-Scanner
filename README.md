# Network-Scanner

Python 3 program (using scapy and argparse) to discover all devices on the network and print their IP and MAC address.

You will need the scapy module for this program to work.
* $ pip3 install scapy

You can run the program using the following command:

* $ sudo python3 netscan-cla.py

Command line takes the following argument:

"-t" (or "--target") indicating the Target IP / IP range, such as:
* --target 192.168.0.1/24
* --target 10.0.2.1/24

[Jason Alway](https://jtalway.github.io)
