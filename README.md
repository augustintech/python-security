# scapy-wifi
Collection of small python scripts, Wi-Fi with scapy.

  - find_devices.py
 # Requirements
 - Scapy library and Python 2 
 - NIC in monitor mode and injection capable
 - Note: For best results use a linux distribution such as Kali Linux.
# Usage

- $ ``` chmod a+x find_devices.py```
- $ ``` airmon-ng start wlan1```
- $ ```./find_devices.py wlan1mon <number of packets>```
