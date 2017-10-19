# TEST ENVIRONMENT & SET UP #

## Table of Contents ##  
[PREPARE THE VM AND HOST](#prepare-the-vm-and-host)  
[PREINSTALLED](#preinstalled)  
[Ubuntu x64 Linux Environment](#ubuntu-x64-linux-environment)  
[References](#references)

## PREPARE THE VM and HOST ##  
### PREINSTALLED ###    

 1. *The IP addresses below are for references. The exactly IP addresses will depend on your local environment.*  

 2. *PLEASE download the image through the **official** website!* Here are the OS images will need:    
 * Kali OS 
 * Ubuntu 16.04 LTS 
 * VM Hypervisor (VMware, VBox, KVM, etc)  
 
 OS | IP Address| OS | IP Address
 --- | --- | --- | ---
 Kali | 192.168.1.28 | Ubuntu 16.04 LTS | 192.168.1.29
 | VM Hypervisor
 HOST | 192.168.1.27 | DHCP server | 192.168.1.1   
 
 3. Guest OS networking Setup: 
Each Guest OS will need **Two Network Adapter**, one for NAT, one for HOST-ONLY(for prepared, if your guest OS and host OS are at different private networks, i.e., Class A and Class C networks)  

### Ubuntu x64 Linux Environment ###  
1. Web Vulnerability 
* OWASP Mutillidae  
> http://[ubuntu linux ip address]/mutillidae/  
* OWASP Juice Shop  
> http://[ubuntu linux ip address]:3000/  
* WEBGoat  
> http://[ubuntu linux ip address]/WebGoat   
* DVWA  
> http://[ubuntu linux ip address]/DVWA/  
> username/password: admin/password  

2. Setting The Environment for Web Vulnerability  
> *Please follow the instuctions below to set up the environment for web vulnerability for above.*    

* [OWASP Mutillidae](https://sourceforge.net/projects/mutillidae/files/mutillidae-project/) 
* [OWASP Juice Shop](https://github.com/bkimminich/juice-shop)
* [WebGoat](https://github.com/WebGoat/WebGoat) 
* [DVWA](http://www.dvwa.co.uk/)  

3. For Successfully setup the environment will be look like below: 
* OWASP Mutillidae  
 ![OWASP Mutillidae](https://res.cloudinary.com/k2745/image/upload/s--PBg3sqZ_--/v1508409537/Mutillidae_rsgg8f)  
* OWASP Juice Shop  
![OWASP Juice Shop](https://res.cloudinary.com/k2745/image/upload/s--NqadHFHr--/v1508409543/JuiceShop_v2k1zb)      
* WebGoat  
![WebGoat](https://res.cloudinary.com/k2745/image/upload/s--1VO-OmNl--/v1508409537/WebGoat_kfoerb)      
* DVWA  
![DVWA](https://res.cloudinary.com/k2745/image/upload/s--hiA13Ri2--/v1508409537/DVWA_cb0crt)     
 
### References ###  
***Warning! This is the web application security penetration test environment only for running those program. While running those program in your machine will be extremely vulnerable to attack. For safety, disconnect from the internet while use those program and this is why the default configuration binds to localhost for minimize the exposure.***  

[OWASP Juice Shop Project](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project#tab=Main)  
[WebGoat Lesson](https://github.com/WebGoat/WebGoat-Lessons)  
[DVWA Project](https://github.com/ethicalhack3r/DVWA)  

