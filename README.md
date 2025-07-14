<p align="center">

![correctsizetransparent](https://github.com/user-attachments/assets/04e6d603-c329-4c36-8bdd-7b43a569ddd6)
</p>

<h1 align="center">Blocking Innapropriate Content on Home Network via DNS Resolver</h1>

<h2 align="center">Overview</h2>

<p>
In a typical home network, when devices connect to the router, the router will automatically configure the DNS settings. The DNS Resolver is usually set to the router's IP address, and the router will forward DNS queries to a DNS Server that is operated by the home network's Internet Service Provider. In this tutorial, the DNS server of a home network router will be manually changed from the ISP's default DNS server to an open-source Cloudflare DNS Server that will automatically filter innapropriate websites.
</p>

<h2>Step-by-step Implementation</h2>

<h3>Step 1: Navigate to the Router's DNS Configuration Settings</h3>

There are a few different ways a router's settings can be accessed. The most common way is to open any browser on any device that is connected to the router and navigate to the router's IP Address. Doing so will bring up the router's web-based interface. Login information may be required to access the settings. Sometimes this information is listed on the back of the router. If not, use [this link](https://www.routerpasswords.com/) to find the login information.

<p align="center">

  ![image](https://github.com/user-attachments/assets/0bf61f2a-99a1-4d8f-b945-3049c2ee86a8)
</p>

<p>
  Some ISP's, like Spectrum for example, use an app to configure the router's settings. Entering the IP address of the router will provide a link to download the app. 
</p>

<p align="center">
  
![routerpage](https://github.com/user-attachments/assets/165d9c76-67eb-4952-92b0-91d7ada1c806)
</p>

<h3>Step 2: Change DNS Settings</h3>

<p>Once the router's settings are opened, navigate to the DNS settings. From here, the DNS servers can be changed manually. Below are the IP addresses of Cloudflare's DNS Servers that filter innapropriate websites.</p>

- 1.1.1.3
- 1.0.0.3

<h3>Step 3: Test the New Configuration</h3>

<p>
  As long as the new settings have been applied, the new DNS resolver can now be tested. Adult websites should now be innaccessible from any device connected to the router. On some devices where adult sites have been accessed previously, the DNS cache on the device will need to be cleared. 
</p>

