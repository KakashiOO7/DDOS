# DDOS_TOOL
---
### Note: python scripts are written in python3. Hence we recommend the use of python3, and pip3 for installing the additional libraries.
---

## Libraries Used

This tool uses a number of python libraries to work properly:
 
* Os

* Scapy - can install with the command:
```sh
$pip3 install scapy
```
* Pandas - can install with the command:
```sh
$pip3 install pandas
```
* numpy - can install with the command:
```sh
$pip3 install numpy
```
* Sklearn - can install with the command:
```sh
$pip install scikit-learn
```
* pickle - can install with the command:
```sh
$pip3 install pickle-mixin
```
## How to Run ?
Install python3, if not already present.

run the ddosdetect.py by typing the following command in a terminal opened in the same folder of
ddosdetect.py file.
```sh
$ python3 ddosdetect.py absolute_path_for_pcap_file
```



## Output

>When the testing gets over, required output.txt file will be generated in the same folder as that of ddosdetect.py,
which contains:
the malicious IP
malicious traffic listed first ( with corresponding frame number in the pcap file, source IP and destination IP)
and then the benign traffic listed ( with corresponding frame number in the pcap file, source IP and destination IP).





