<p align="center">
<img src="https://i.postimg.cc/BvThz3h9/Screenshot-2023-11-15-000000.png"/>
</p>

<h1>Virtual Machine + VPN</h1>
This tutorial is a brief walk-through for installing a VPN (Virtual Private Network) on a VM (Virtual Machine)<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN (Free Version)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Off-screen step:</h2>

- It's probably advantageous to go ahead and create your protonvpn account on your actual computer before you actually install it on your virtual machine. For all intents and purposes of keeping my credentials private, this tutorial begins after the creation of the ProtonVPN "Free" account, which you can create <a href="https://protonvpn.com/">here</a>. 

<h2>Walkthough</h2>

<p>
<img src="https://i.postimg.cc/QxG7n7WP/Screenshot-2023-11-14-230815.png"/>
</p>
<p>
  
First thing's first, we'll go ahead and create our virtual machine in Azure. For this demonstration, we're using Windows 10. Then, we're going to go ahead and connect to it in Remote Desktop via port 3389.
</p>
  
<p>
<img src="https://i.postimg.cc/qBCnLwgy/Screenshot-2023-11-14-231434.png"/>
</p>
<p>
  
Obviously, its IP address is how we establish that connection, but just to verify for educational purposes, I've done a quick "What's my IP address?" search, and it's yielded the exact number we would have expected the IP address to be. 172.174.231.250 - out of lovely Washington, Virginia.
</p>
<br />

<p>
The next step is to head on over to Protonvpn.com on our VM, and download the version appropriate for its operating system.
</p>
<p>
<img src="https://i.postimg.cc/tTs68tk0/Screenshot-2023-11-14-232815.png"/> <img src="https://i.postimg.cc/4N6cC363/Screenshot-2023-11-14-233001.png"/>
</p>
<br />
Once downloaded, we'll open the file and run through its installation + setup Wizard.


<p>
Once the application has installed, you can then enter your credentials previously established with protonvpn, and log right in. If you haven't already created an account with protonvpn, you should be able to through the application itself.
  
  <img src="https://i.postimg.cc/rsWYGfVV/Screenshot-2023-11-15-003351.png"/>
</p>
<br />

<p>It is limited, being a free service, but of course you do have a few options to explore. For this demonstration, I eventually chose to connect to the Japanese server, and then asked bing what my IP address was yet again.
  <img src="https://i.postimg.cc/sxShgjbw/Screenshot-2023-11-14-234933.png"/>
  <img src="https://i.postimg.cc/4xX9XTPQ/Screenshot-2023-11-14-235038.png"/>
 
  Success! Clearly, the VPN does its job. So well so, that the default loading browser is in a completely new language without meddling in any additional settings. 
  Any step in adding security to your internet use is certainly a step in the right direction. Now you can do so confidently with a virtual machine!
</p>
