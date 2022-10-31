# Infrastructure-as-a-code-using-Vagrant

# Steps

Step 1 - Create a vagrant directory.

Command: mkdir vagrant

Step 2 -Create another directory inside vagrant-vms

Command: mkdir IAAC

Step 3 - Create two directories inside IAAC

Command: mkdir website

Step 4 - Change directory to website

Command: cd website

Step 5 - Create a vagrantfile inside wordpress directory 

Command: vagrant init centos/7

Step 5 - Use vim editor to modify the vagrantfile IP address, enable bridge adapter, and upload the website link.

![IAC](https://user-images.githubusercontent.com/52894481/184517079-6f222064-0e99-490f-8f34-cd6fe7249267.PNG)

Step 6 - Start the VM

Command: vagrant up

![IAC VM UP](https://user-images.githubusercontent.com/52894481/184517072-a5571520-51af-4e45-9e29-7015601e888a.PNG)

Step 7: Access the website from the browser using the VM's IP Address.

![IAC WEB](https://user-images.githubusercontent.com/52894481/184517085-ecdb3cc8-8eb1-491c-b2bc-cc7ac312dec9.PNG)





