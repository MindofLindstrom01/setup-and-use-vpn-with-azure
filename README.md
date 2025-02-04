<p align="center">
  
![image](https://github.com/user-attachments/assets/73ca7eaf-2430-41ed-bb70-63b5271d71fa)

</p>

<h1>Setup and Use a VPN</h1>
<h2>Description</h2>
In this project I create an Azure VM (Virtual Machine) where I download, install, and use a free VPN (Virtual Private Network) called ProtonVPN.<br>
<br />
VPNs (Virtual Private Networks) allow you to connect to a network through encrypted tunnels, enhancing security. Two commons ways VPNs are used are, for companies to allow for remote work, and accessing different content that otherwise would be unavailable without a VPN.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Virtual Machine
- Remote Desktop Connection
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2)

<h2>Project Walk-Through:</h2>

<h3>Step 1.</h3>

![1  click create new vm](https://github.com/user-attachments/assets/e478d2ac-cf0b-4410-96ce-82f63d31a925)

<p>Click create a new Azure virtual machine</p>

<h3>Step 2.</h3>

![2  vm details](https://github.com/user-attachments/assets/c425774f-0e67-4f98-bb92-8e67b471b00e)

<p>Click create new resource group and name it, name the virtual machine, select the region, select Windows 10 Pro version 22H2, select a size of 2vcpus 8 GiB memory</p>

<h3>Step 3.</h3>

![3  enter vm user   pass](https://github.com/user-attachments/assets/a4b9f83a-7f53-4325-90ed-ceda357e525b)

<p>Create a username and password for this vm, check the box, then click Review + create</p>

<h3>Step 4.</h3>

![4  create vm](https://github.com/user-attachments/assets/daf2c490-cd1f-4645-b5be-5213a3806627)

<p>Click create</p>

<h3>Step 5.</h3>

![5  vm created](https://github.com/user-attachments/assets/4cecd684-f8ed-4328-b9aa-1f33bcdcdd98)

<p>The vm has been deployed, click go to resource</p>

<h3>Step 6.</h3>

![6  get public ip](https://github.com/user-attachments/assets/81c7c557-92cc-4db5-b670-a19fe85c4ded)

<p>Grab the public IP of the vm</p>

<h3>Step 7.</h3>

![7  click connect in rdc](https://github.com/user-attachments/assets/9d586365-7c34-40e4-bc52-eb83a9b7f33a)

<p>Enter the public IP into Remote Desktop Connection, then click Connect</p>

<h3>Step 8.</h3>

![8  enter vm credentials](https://github.com/user-attachments/assets/6ad56a87-48e0-4950-81bf-4ac372de7991)

<p>Enter the username and password then click OK</p>

<h3>Step 9.</h3>

![9  native ip info](https://github.com/user-attachments/assets/f1764d90-5d09-49e4-9489-e721385ddf0c)

<p>Go to your native machine and go to whatismyipaddress.com, This will show your public IP and location</p>

<h3>Step 10.</h3>

![10  vm ip info](https://github.com/user-attachments/assets/6fc16d46-267d-40a3-95e0-b746a9e2008e)

<p>Now go to the same website within the VM we connected to. This will show your VM's public IP and location.</p>

<h3>Step 11.</h3>

![11  signup for vpn](https://github.com/user-attachments/assets/44b60266-eab1-4c69-84f2-03a742e12288)

<p>Inside the VM, search for ProtonVPN and create an account</p>

<h3>Step 12.</h3>

![12  set pass](https://github.com/user-attachments/assets/c3e10158-cacb-4b89-ab0e-11898e460512)

<p>Create a username and password for the account</p>

<h3>Step 13.</h3>

![13  download vpn](https://github.com/user-attachments/assets/758540bf-c903-476f-9088-bdd573a5b3ae)

<p>Click download</p>

<h3>Step 14.</h3>

![14  click download](https://github.com/user-attachments/assets/58a100c5-8026-4d5f-9293-9db8cb02f650)

<p>Click dowload for Windows</p>

<h3>Step 15.</h3>

![15  open file](https://github.com/user-attachments/assets/6a80a689-30a5-436a-a5e3-b6e604175951)

<p>Open the newly downloaded .exe file</p>

<h3>Step 16.</h3>

![16  click install](https://github.com/user-attachments/assets/bd4933b1-46b4-404a-a8e2-07a10357e2f1)

<p>Run the setup and click Install</p>

<h3>Step 17.</h3>

![17  sign in to vpn](https://github.com/user-attachments/assets/a2783368-d210-4c05-b588-baf19434a06a)

<p>Sign in to your newly created account</p>

<h3>Step 18.</h3>

![18  click connect under fastest](https://github.com/user-attachments/assets/d3761919-2eea-404e-a9c4-16d8e122b9e4)

<p>Find the fastest option and click connect</p>

<h3>Step 19.</h3>

![19  connected to Romania](https://github.com/user-attachments/assets/24a8f666-03f5-47e1-97f1-4a9a56cefcc7)

<p>The VPN has successfully been established to a server in Romania</p>

<h3>Step 20.</h3>

![20  vm vpn ip info](https://github.com/user-attachments/assets/7030f01a-0368-4b00-b348-51c276882756)

<p>Now go back to the website whatismyipaddress.com and see your new public IP and location</p>

<h2>VPN Setup Complete!</h2>

<p>In this project, we've successfully created a virtual machine running Windows 10. We downloaded, installed, and used a free VPN called ProtonVPN. We observed all of the different changes that happened with our IP address and location with our native machine, virtual machine, and the virtual machine using a VPN.</p>





























