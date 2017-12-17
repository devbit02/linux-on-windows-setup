# linux-on-widow-setup
This is my setup for running Linux on Windows using VirtualBox and Vagrant.  Vagrantfiles builds up a virtual machine with only the applications needed, allowing for quick and repeatable setup for the exact environment needed.

## Setup
1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
2. Download and install [Vagrant](https://www.vagrantup.com/downloads.html).
3. Download Vagrant file from [this list](https://github.com/devroger/Vagrantfiles).

## Running the virtual machine
Using the command line, find the directory for the downloaded Vagrant file and run the following commands to spin up a new linux box (vagrant up) and ssh into it (vagrant ssh).
```
$ vagrant up
$ vagrant ssh
```

## Shutting down the virtual machine
First exit the virtual machine by typing "exit" at the command prompt:
```
$ exit
```
Now you can safely shut down your virtual machine with the following command:

```
$ vagrant halt
```
