# Federated Learning
IDK why but I can only use the libraries in linux environment

## Here's the guide on how to set up the environment in WSL
------------
### Update your package list:
``` sh
sudo apt update && sudo apt upgrade -y
```

### Install Python 3.11 using the deadsnakes PPA:
``` sh
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt install python3.11
```

### List All Installed Python Versions
To find all Python versions installed on your system
``` sh
ls /usr/bin/python*
```

### Create a Virtual Environment Using Python 3.11
``` sh
python3.11 -m venv venv
```

##### Note: If you encountered a problem with pip, use the command below, then try to create an environment again
``` sh
sudo apt update
sudo apt install --reinstall python3.11 python3.11-venv python3.11-distutils
```

### Activate the Virtual Environment
``` sh
source venv/bin/activate
```

### Install the requirements
``` sh
pip install -r requirments.txt
```