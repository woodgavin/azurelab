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
* Refreshing the page should show the RG.
* Navigate to VMs.
![](/assets/4.png)
* Create single machine.
![](/assets/5.png)
* Assign to created RG. #
* Name VM `user-vm-1`. #
* Set username/password to: `labuser`/`Cyberlab123!` #
  * user/pass only provided for lab documentation. Never store passwords in plaintext documents on any machine!
* Select a correct size for VM. #
* Review and create ##
* I am currently using Ubuntu, so I will use Remmina to remote in.
* Click on the VM. #
* Find Public IP adress. #
* Add new connection. #
* Fill in details #
* trust certificate 
* Log in.
* Go through MS boot options.
