
# ChRIS Development Setup

### Prerequisite docker, not podman

As big of a fan of podman/kubernetes that I am, this is a docker project, not a podman project. 
I recommend installing docker instead. 


### Clone the issues-chris repository to start developing for ChRIS. 

```bash
sudo install -d -o $USER -g $USER /usr/local/src/issues-chris
git clone git@github.com:team19hackathon2021/issues-chris.git /usr/local/src/issues-chris
cd /usr/local/src/issues-chris
ansible-playbook -K chris_dev_setup.yml
```

