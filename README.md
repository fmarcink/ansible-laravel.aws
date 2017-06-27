# ansible-laravel.aws

Tested on Debian-based Ubuntu 16 platform.

Ansible playbook for installing laravel + dependencies on remote server (or in this case aws instance) 

Recommended run apt-updates.yaml and beginning and end of sequence.

Ideal Progression:


1. apt-updates.yaml
2. php.yaml
3. git.yaml
4. composer.yaml
5. laravel.yaml
6. apt-updates.yaml
