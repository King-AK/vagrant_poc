# vagrant_poc
Dummy repo to play around with Vagrant on Ubuntu/Debian


Steps:
* Install virtual box and vagrant if they are not already installed using 
```bash
bash setup/install_virtualbox_and_vagrant.sh
```
* Create a python3.9+ virtual environment
* Use pip to install `ansible`, `psycopg2-binary`
* Install the `ansible-galaxy` `community.postgresql` module
```bash
ansible-galaxy collection install community.postgresql
```
* `cd` into `vagrant` directory, run `vagrant up`