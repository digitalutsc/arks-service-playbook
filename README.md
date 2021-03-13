# Ark Services Playbook

## Installation

* Clone this repo to your machine, by running:

```
git clone https://github.com/digitalutsc/ark-services-playbook.git
```

* To run the VM, cd `path/ark-services-playbook`, then run `vagrant up`

* When VM is running, to remote access run `vagrant ssh`
    * After access the VM, run `sudo nano /etc/hosts`, then adding the following:
    ```
        127.0.0.1       ark.demo
    ```
    * Enable `curl` extension for PHP of the VM: 
      * Run `sudo nano /etc/php/7.4/apache2/php.ini`
      * Add `extension=curl` to the file.
    * Restart apache by running `sudo service apache2 restart`

* In local machine, 
    * Run `sudo nano /etc/hosts`, add 
    ```
        127.0.0.1       ark.demo
    ```
    * To initial setup for the application, go to http://ark.demo/admin/install.php.
    * To start using the application, go to http://ark.demo/admin/admin.php.

## Usage

Please visit full documentation at https://github.com/digitalutsc/ark-services/wiki#usage


