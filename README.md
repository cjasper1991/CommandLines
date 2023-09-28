# CommandLines
<p align="center">
<img width="265" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/f336145d-8896-43b2-8873-9a39722882fe">

</p>

<h1>Command Lines for network</h2>

This tutorial outlines some command line prompts.<br />




<h2>Environments and Technologies Used</h2>

- Command Prompt 
  

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Command Lines </h2>

PING 

 <img width="531" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/50d168c6-cce6-42d2-aea2-3bac8773ab34">

</p>
<p>
Used to test for connectivity between two devices.
</p>
<br />

PING -a

<img width="399" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/1ecce7cc-94d2-46f2-9703-34c0efd0acec">

</p>
<p>
The -a parameter tests for name resolution.Use it to display host name and verify DNS (Domain Naming System) is working.
</p>
<br />

Ping -t

<p>
<img width="509" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/f34b024a-cc52-417a-b46a-8e64b8a5fae9">

</p>
<p>
The -t parameter causes pinging to continue until interrupted.

  ipconfig /all
  
<img width="705" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/21f00ef1-7ced-4c80-bb15-92ac9afbc565">

</p>
<p>
Displays TCP/IP information.
</p>
<br />

ipconfig /release

<img width="710" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/6e5573f3-bbc6-4495-9152-456bfb10baf1">

</p>
<p>
Releases the IP address when dynamic IP adressing is being used.
</p>
<br />

ipcongfig /renew

<p>
<img width="749" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/6b730acc-1c3b-490c-a952-aa14d10e2142">

</p>
<p>

Leases a new IP address from a DHCP server. Make sure you release the IP address before you renew it.

ipconfig /displaydns

<img width="395" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/d78b56fc-18d3-4577-b9e1-d0c4e4414a05">

</p>
<p>
Displays information about name resolutions that Windows currently holds in the DNS reolver cache.
</p>
<br />

ipconfig /flushdns

<img width="332" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/6d39fc4a-4a41-48c0-8287-195b5a6bdf72">

</p>
<p>
Flushes the name resolver cache, which might solve a problem when the browser cannot find a host on the internet.
</p>
<br />

nslookup

<img width="586" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/2b3b3f60-14cd-410c-b06d-38c36ed66a53">

</p>
<p>
Used to query Domain Name System (DNS) to obtain domain names or IP addresses, mapping or for any other specific DNS Records.

nslookup Microsoft.com

<img width="541" alt="image" src="https://github.com/cjasper1991/CommandLines/assets/126079527/f06b4e80-5922-4236-bd9a-1788e11aa971">



Used to find a record of domain.
</p>
<br />
