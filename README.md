# evething-2 Server Setup

## Create a new VM on [Google Compute](https://console.cloud.google.com/compute/instancesAdd)

  - Recommended settings:
    - 1 vCPU
    - 3.75 GB RAM
    - Debian GNU/Linux 9 (stretch) OS
    - Allow HTTP traffic

## After the new VM is running, SSH to it and run these command:

```bash
sudo apt-get -y update
sudo apt-get -y install git
git clone https://github.com/x1s7/evething-2-server-setup
sudo ./evething-2-server-setup/setup.sh
```
