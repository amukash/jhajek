# Tooling Assignment Vagrant

## Initial Setup and Configuration

Screenshot of :
Ran vagrant init bento/ubuntu-22.04
Have a generated Vagrantfile
Used vagrant plugin install vagrant-parallels

![*Vagrant init & Plugin install*](./images/Screenshot_1.png)

![*generated vagrantfile*](./images/Screenshot_1b.png)

## Running the VM

Screenshot of:
ran vagrant up
successfully SSH’ed into the box using vagrant ssh

![*vagrant up & vagrant ssh*](./images/Screenshot_2.png)

## WebServer Install

Screenshot from:
the host OS of http://192.168.56.10 or comparable URL
sudo apt-get update and sudo apt-get install nginx
Nginx installation succeeded

![*host OS private-network*](./images/Screenshot_3f.png)
![*sudo apt-get update*](./images/Screenshot_3.png)
![*sudo apt-get install nginx*](./images/Screenshot_3b.png)
![*Nginx installation*](./images/Screenshot_3e.png)

## Editing Vagrantfile

Screenshot of:
Line 35 (private network) is uncommented and set to IP like *192.168.56.10*
Line 59, 64, and 65 are uncommented and memory is set to 2048 or 4096

![*Editing*](./images/Screenshot_4.png)

##  Reset and Verify Destruction

Screenshot of:
vagrant halt
vagrant destroy
vagrant up
vagrant ssh
sudo systemctl status nginx — showing Nginx is not installed

![*Reset & Destroy Verification*](./images/Screenshot_5.png)

## Output of vagrant box list command

After completing this tutorial take a screenshot of the output of the command ```vagrant box list```

![*vagrant box list*](./images/Screenshot_6.png)


