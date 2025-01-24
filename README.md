# Docker Tutorial for [DIAL-MPC](https://github.com/LeCAR-Lab/dial-mpc)

This repository contains the Dockerfile of the DIAL-MPC.
DIAL-MPC is an impressive framework for legged robot ***full-order torque-level*** control with both precision and agility in a ***training-free*** manner.
You can find the DIAL-MPC in [here](https://github.com/LeCAR-Lab/dial-mpc).

## Requirenments
> [!CAUTION]
> You need a Linux or Ubuntu system with Nvidia-driver (>=525.60.13)

## Docker and Nvidia-toolkit installation
### Step 1. Docker install
``` bash
curl -fsSL https://get.docker.com -o get-docker.sh
sudo bash get-docker.sh
``` 
### Step 2. Docker Postinstall(Follow [here](https://docs.docker.com/engine/install/linux-postinstall/))
### Step 3. Docker Nvidia Toolkit

### Step 4(Optional).Install xhost
``` bash
sudo apt install x11-xserver-utils
```
## Build Docker Env
``` bash
git clone https://github.com/XuXinhangNTU/dial-mpc-docker
cd dial-mpc-docker
docker build -t dial-mpc .
docker run -it -v 
```
