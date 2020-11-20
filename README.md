## VAK (Vagrant, Ansible, Kubernetes)

### What is this?

A Vagrant environment for setting up a simple single master, 2 worker, Kubernetes cluster.

<b>This is NOT my original work!</b>

I needed to learn a little Ansible, and Kubernetes, and found [this awesome blog entry](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/) by Naresh L J (from Infosys).

When walking through the article I found a couple problems, minor ruby syntax error, and a couple changes needed for the current Ansible and Calico versions I'm using.

### Requirements
* Virtualbox
* Vagrant
* Python 3.x

### How to run it
* `python3 -m venv venv`
* `source venv/bin/activate`
* `pip install -r requirements.txt`
* `vagrant up`
* `vagrant ssh <machine_name>`
