There are readmes for each of the installer directories.

Quick Start

```bash
./azure/build_azure_linux_network.py -g your-group-name -s 0.0.0.0 -vs Standard_D8_v4 -l westus -ast 00:00
./minimega/install.sh lme-user  $(cat your-group-name.ip.txt) your-group-name.password.txt
./ubuntu_qcow_maker/install.sh lme-user $(cat your-group-name.ip.txt) your-group-name.password.txt
```