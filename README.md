
                                  -------------------------------------------------------------------------------------

Amazon Web Services:
           cloud service privider,
           cloud computing platform
           Web hosting
           servers 
           data storage
           devloping tools
           security
          cloud computing:
           Delivery of computing services
           To store the large amount of data
           To access data at any place at any time
           go global in minutes
          it is the on demand delivery of it resoures over the internet with pay as you go pricing

Examples of cloud providers:Aws ,Azure,google cloud
 
real time examples:
      banking,email,media...etc
bussiness side:Applications,
      infrastructure,storage,sales..etc
->1994 amazon.com
->2004 aws services started.
SQS was the initial service in aws later AWS Services:data storage,security,ec2..etc



Advantages of Cloud computing:
          Security,low cost,access any where any time.
          scalability,easily manageble,reliable,data storage,24*7 avalable
          flexible of work practices




AWS spread over 20 Regions(contries)
in india Availability Zones are (mumbai,chennai)








                                        -----------------------------------------------------------------------------------
                    ....steps for creating servers....
-click on services
-select ec2
-click on instances
-launch instance
-select choose ami(ubuntu)
-choose instance type(free tier t2 micro)
-configure instance details(default) ...click on next
-add storage(default) ...click next
-add tags for remeber(we can as our names) ...click on next
-configure security group(click on add rule and select http
						select https and also select source to anywhere) ...click on review and launch
-...click on launch
-select new key pair.and give a name ..click on download key pair
-click on launch instance

.......
STEPS FOR CONNECTING TO SERVER
.......
-download putty.exe and puttygen.exe
		putty is the terminal emulator
					elumilator is a computing an emulator is hardware or software that enables on computer hosting
		putty supports public key authentication
		putty is most popular ssh client.
---INSTALLING and CONNECTING  PUTTY and PUTTYGEN---
open putty gen:
		-click on load and select .pem file and click save private key..
open putty:
		-Go to running instances in aws console and copy the public ip address and paste it in putty
		-select auth in ssh in putty category
		-click on browse and select .ppk file then you get terminal
    -then putty is in active state.we have to enter command based on type of servers
.
                                ----------------------------------------------------------------------------------
      
      
      -----------ubuntu server commands--------
      
.login as:ubuntu	      	|
sudo su			             	|
apt-get update		      	|	these are commands in putty terminal
apt-get install apache2		|
service  apache2 start		|




    -------------linux server commands-------
login as:ec2-user			                       |
sudo su					                             |
sudo amazon-linux-extras install nginx1	     |			these are comands used in putty terminal			 |
service nginx start			                     |
		
		 

