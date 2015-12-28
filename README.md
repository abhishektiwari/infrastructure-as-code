# Infrastructure as Code
This project is a skeleton for infrastructure as code implementations. You can use it to quickly bootstrap your own infrastructure as code projects.

The seed contains a sample infrastructure as code implementation which includes,

- Git for versioning infrastructure as code 
- Terraform, CloudFormation, YAML and Python Scripts for infrastructure provisioning
- Puppet/Chef for configuration management 
- Docker for container management
- Fabric/Capistrano for remote execution and deployment
- Vagrant for local testing and development using Puppet/Chef solo
- Jenkins for continuous integration of infrastructure  
- A hello world example to provision and configure a Nodejs application

# Prerequisites

## Git
You need Git to clone this seed repository. You can get git [here](http://git-scm.com/). For the Puppet modules and Chef cookbooks, we are using [Git submodules](https://git-scm.com/docs/git-submodule).

### Updating submodules

All submodules,

```
git submodule foreach --recursive git pull
```

A specific module,

```
cd your/submodule
git pull origin master
```

## Virtualbox and Vagrant

You will need to install Virtualbox and Vagrant.


## Python Virtualenv

- Python `2.7.x` and `pip` installed on your local machine
- Once you have Python and `pip` please install `virtualenv` as described here

# I don't want ...
I don't want some of the folders in this seed, well just add folder name or pattern in `.gitignore`

# To Do

- Ansible/Salt for configuration management
- MEAN stack as an example 
- LAMP stack as an example
- .Net stack as an example
