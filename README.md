# Network-Scanner

Python 3 program (using scapy and argparse) to discover all devices on the network and print their IP and MAC address.

## Dependencies

```
$ sudo apt-get install python3-scapy
```

## Usage

```
$ sudo python3 netscan-cla.py --target 192.168.0.1/24
$ sudo python3 netscan-cla.py -t 10.0.2.1/24
```
#### Arguments
`-t` (or `--target`) indicating the Target IP / IP range

