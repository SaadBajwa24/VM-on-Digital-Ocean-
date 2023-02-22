# VM-on-Digital-Ocean-
Creating and Accessing a Cloud-hosted Linux Virtual Machine on Digital Ocean

-> After filling in my details. I was welcomed to dashboard of Digital Ocean.

-> By clicking on create button as shown below I was shown a list of services. From there, I selected Droplets.

-> Then, chose the appropriate region, datacenter, size, CPU options, authentication method to SSH etc. At last clicked on Create Droplet button.

-> Droplet is created.

**Configuration of SSH keys:**

-> I added SSH key by using Putty.

-> Download Putty from the browser.

-> Now run Puttygen. Once opened, click on generate to generate the public key.

-> Once, public key is generated enter the passphrase and click save private key to save your private key in a secure place.

-> Public-Private key pair is generated.

**Accessing VM using SSH:**

-> I accessed VM by using Putty.

-> Run Putty. Enter the IP Address in the text box.

-> Then scroll down to Auth from the left dropdown and select Credentials from there. Then, click on browse and select the private key file that you saved when generating the public-private key pair.

-> Now return to Session from the left dropdown and click on open.

-> Enter the username and passphrase to authenticate.

**Firewall Configuration:**

-> I configured firewall by using DigitalOcean.

-> Click on networking from the left-drop down.

-> Then select firewall and click on create firewall button.

-> Now, give it a name, set the inbound and outbound rules according to your needs, select the droplets to which this firewall should be configured, and at last click on create firewall. The first Inbound rule that I added was to allow HTTP connections at 80 port and other was to allow RPD protocol at port 3389.

-> Firewall is created.

**Installing RDP in VM and accessing the VM using RDP from your PC:**

-> I installed and accessed my VM by using RDP.

-> Run Putty. Enter the required details and open it to configure your terminal. Install xfce and xfce-goodies package on your server as shown below.

-> Once installed, now install another package xrdp as shown below.

-> Now, verify the status of xrdp as shown below.

-> Now, configure your xrdp by following the commands as shown below.

-> Now, to test the RDP connection enter Remote Desktop Connection in the search bar and open it. Enter the IP address and the username.

-> Click on Connect. Enter password and you would be able to access it.

**Hosting Files (Any type) using a simple HTTP Server, and accessing using public IP:**

-> I hosted and accessed my VM by using Apache server.

-> Install Apache on VM using terminal.

-> Let’s change the HTML to our HTML. For that go to RDC connection and access the VM. Open Filesystem, then open var, then open www, then open html and finally open html file.

-> Edit HTML.

-> Now, access it using Public IP.

-> Task Finished!
