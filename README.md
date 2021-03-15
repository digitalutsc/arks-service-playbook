# Ark Services Playbook

## About

This is the Ansible playbook for Ark Services web application (https://github.com/digitalutsc/ark-services).

## Installation

1. Open a Terminal, clone this repo to your machine, by running:

```
git clone https://github.com/digitalutsc/ark-services-playbook.git
```

2. To run the VM, `cd path/ark-services-playbook`, then run `vagrant up`.
3. When VM is running, to remote access run `vagrant ssh`
    * After access the VM, run `sudo nano /etc/hosts`, then adding the following:
    ```
        127.0.0.1       ark.demo
    ```

4. In your machine: 
    * Run `sudo nano /etc/hosts`, adding the following: 
    ```
        127.0.0.1       ark.demo
    ```

5. To initial setup for the application, go to http://ark.demo/admin/install.php.
6. To start using the application, go to http://ark.demo/admin/admin.php.

## Usage

Please visit full documentation at https://github.com/digitalutsc/ark-services/wiki#usage


