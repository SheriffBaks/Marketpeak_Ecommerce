# Marketpeak_Ecommerce
This Project is to develop an e-commerce website caled MarketPeak using Git, Linux which will be deployed on an AWS EC2 instace. 
The process of doing that are as follows:

### 1. Implement Version Control with Git
  
 1.1 *Creation of project directory named **Marketpeak_Ecommerce***

   > [Creation of Directory and Initializing Git](./IMG/1.%20Creation%20and%20Initiazing%20git.png)

1.2 *Prepare website folder in the Marektpeak folder.* Website folder was moved to the project folder here

   >[Website Folder](./IMG/2.%20Website%20folder.png)

1.3 *Stage and Commit website structure to git*

   >[Stage and commit](./IMG/3.%20Stage%20and%20Commit%20.png)

1.4 *Pushing the code to Github Repository*
    . *This is done after creating a **MarketPeak_Ecommerce** repository on Github and linking local repository to Github with the following command*

  > [Push to Github Repository](./IMG/4.%20Push%20to%20GitHub%20Repository.png)

### 2. AWS Deployment

2.1 *Setup an AWS EC2 Instance*

*I logged into my AWS Management Console, launched an EC2 instance using Amazon Linux AMI and connected to the instance using SSH*

> [Connect USing SSH](./IMG/5.%20Connecting%20EC2%20Instance.png)

2.2 *Cloning my Github repository on the Linux Server i deployed* 

*Before deploying my e-commerce platform, i cloned my Github repository to my AWS EC2 instance. This process involves authenticating with Github and choosing between two primary methods of cloning a repository: **SSH and HTTPS.** I decided to use the **SSH** Method. This involves generating the SSH keypair using ssh-keygen, displaying and copying the public key and adding public key to your Github account and then using SSH clone URL to clone repository.*

> [SSH Keypair](./IMG/6.%20SSH%20Keypair.png)

> [SSH Public Key](./IMG/8.%20SSH%20Public%20Key.png)

*In my case i had to install git on my EC2 instance before proceeding with the git commands*

> [Installing Git](./IMG/9.%20Install%20Git%20before%20cloning%20.png)

> [Github Repository Cloning](./IMG/10.%20Github%20Cloning.png)

2.3 *Installing a Web Server on EC2*

*Apache HTTP Server (httpd) web server that serves HTML files and content over the internet was used to host the the Market E-commerce site.*

> [Installing HTTP Server](./IMG/11.%20Install%20HTTP%20Server%20(httpd).png)

2.4 *Configuring httpd for Website*

*httpd was configured to point to the directory on Linux server where website code files are stored. Usually in /var/www/html.*

> [httpd for Website](./IMG/12.%20Configure%20httpd%20for%20Website.png)

> [Got httpd server to run](./IMG/rename%20folder.png)

2.5 *Accessing Website from Browser*

*I was able to load website from a browser using the public ip address from my EC2 including name of folder housing the website files.*

> [Website Unveiling](./IMG/13.%20Website%20page.png)

3. *Continuous Integration and Deployemnt*

*I'm Developing new features and fixes for the website and doing that by using a new branch named developmet*

> [New Brancc Created ](./IMG/14.%20New%20Branch.png)

>[Git add and commit changes](./IMG/15.%20Git%20add%20and%20commit%20.png)

> [Git Push Changes](./IMG/16.%20Git%20push.png)

> [Merge changes](./IMG/17.%20To%20mend%20changes.png)

> [Change to main Branch and ](./IMG/18.%20To%20change%20to%20Main%20branch.png)


  
