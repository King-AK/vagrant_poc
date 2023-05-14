# vagrant_poc
Dummy repo to play around with Vagrant on Ubuntu/Debian


Steps:
* Install virtual box and vagrant if they are not already installed using 
```bash
bash setup/install_virtualbox_and_vagrant.sh
```
* Set up and configure python venv, use pip to install ansible requirements
```bash
python3 -m venv ./venv
source ./venv/bin/activate
pip install -r requirements.txt
```
* `cd` into `vagrant` directory, run `vagrant up`
* To delete the vm run `vagrant destroy`

TODO:
ADO Pipeline with Junit and Visualization