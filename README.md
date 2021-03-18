# Ansible_Nodejs
Testing with Vagrant, Ansible and Nodejs

Clone down repo, cd in to repo execute ```vagrant up``` this will build the vm using the Ansible playbook in provisioning.

The follwoing tasks will be ran on the VM 
1.Install EPEL repo.
2.Import Remi GPG key.
3.Install Remi repo.
4.Ensure firewalld is stopped (since this is a test server).
5.Install Node.js and npm.
6.Install Forever (to run our Node.js app).
7.Ensure Node.js app folder exists.
8.Copy example Node.js app to server.
9.Install app dependencies defined in package.json.
10.Check list of running Node.js apps.
11.Start example Node.js app.
