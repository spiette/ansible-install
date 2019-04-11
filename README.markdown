# ansible-install

# Description

`ansible-install` provides a generic role to install software provides as already compiled software, and a collection of already made invocations for the following:

- terraform
- terragrunt
- helm
- ct
- minikube
- rke
- go-jira
- cfssl
- cfssljson
- gcloud
- k9s

It will keep the tarballs and other archives in `~/.cache/install`. Binaries will be installed in `~/bin`. No root privileges required. Look in `roles/install/defaults/main.yml` for usable variables.

## Requirements

`ansible >= 2.7`

## Usage


    ansible-playbook site.yml
