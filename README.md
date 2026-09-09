# Azure Compute and Networking Lab

The goal of this lab is to create a Resource Group(RG) in Azure, then create a Virtual Machine(VM) within the RG and remotely connect to it.

![](/assets/1.png)

* Click RG
![](/assets/1.png)
* Click Create
![](/assets/2.png)
* Name RG `Azurelabs`. I will use this RG for all other projects as well.
![](/assets/3.png)
* Review and Create. Create.
![](/assets/3.png)
* Refreshing the page should show the RG.
* Navigate to VMs.
![](/assets/4.png)
* Create single machine.
![](/assets/5.png)
* Assign to created RG.
* Name VM `user-vm-1`. 
* Select a correct size for VM. (Recommended 2vCPUss and 4GiB minimum)
    * If no options are available to pick from, click `See all sizes` to get a list of available options.
![](/assets/6.png)
![](/assets/6.1.png)
![](/assets/7.png)
* Set username/password to: `labuser`/`Cyberlab123!`
  * user/pass only provided for lab documentation. Never store passwords in plaintext documents on any machine!
![](/assets/9.png)
* Review and create. Create.
![](/assets/8.png)
![](/assets/10.png)
* Click on the VM after it has been finalized.
* Find Public IP adress.
![](/assets/11.png)
* I am currently using Ubuntu, so I will use Remmina to remote in.
* Add new connection.
![](/assets/12.png)
* Fill in details
    * Even though there is an option to add a username and password, I will leave these blank to be able to easily log into other users as well from the same profile.
![](/assets/13.png)
* trust certificate 
* Log in.
* Go through MS boot options.
