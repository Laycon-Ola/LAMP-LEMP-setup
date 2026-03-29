**ASSIGNMENT 2 - Install the LAMP & LEMP Stack or Web Server on my EC2
Instance.**

**LAMP STACK INSTALLATION**

**STEP 1 - ssh into my instance**

![](assets/media/image1.png)

**STEP 2 - Performed a quick software update of dependencies on my
instance**

![](assets/media/image2.png)

**STEP 3 - Installed the Database -MariaDB**

![](assets/media/image3.png)

![](assets/media/image4.png)

**STEP 4 - Installed Apache Web Server**

![](assets/media/image5.png)

![](assets/media/image6.png)

**STEP 5 - Installed the PHP software**

![](assets/media/image7.png)

![](assets/media/image8.png)

**STEP 6 - Started the Apache web server**

![](assets/media/image9.png)

**STEP 7 - Configured the Apache web server to always start at each
system boot.**

![](assets/media/image10.png)

**STEP 8 - Ensured my vpc security group and my instance NACL allowed
inbound Http port 80 traffic**

![](assets/media/image11.png)

![](assets/media/image12.png)

**STEP 9 - Typed in my EC2 instance public IP address in the browser**

![](assets/media/image13.png)

N.B - The traffic btw the web server and browser is not secured because
Apache doesn't configure SSL by default.

**LEMP INSTALLATION**

**STEP 1 - ssh into my instance and ran the command to install nginx**

![](assets/media/image14.png)

![](assets/media/image15.png)

STEP 2 - Started the nginx web server but got an error

![](assets/media/image16.png){width="5.760416666666667in" height="2.95in"}

This was because Apache was occupying port 80. So, I stopped the Apache
web server before spinning up the nginx again

STEP 3 - Stopped the Apache web server

![](assets/media/image17.png)

STEP 4 - Nginx Web Server started successfully

![](assets/media/image18.png)

Nginx successfully deployed with EC2 instance public IP

![](assets/media/image19.png)
