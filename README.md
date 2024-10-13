# ubuntu-docker
Ansible role to install Docker on linux (Ubuntu) servers

## Installation

Create requirements.yml file

```
# Include ubuntu-docker role
- src: https://github.com/FastMT/ansible-ubuntu-docker.git
  name: ubuntu-docker
  version: "v1.0.3"
```

Install external module into ~/.ansible/roles folder

```
ansible-galaxy install -r requirements.yml
```

## Usage

playbook.yml:

```
# Install docker on linux servers
- role: "ubuntu-docker"
```   
