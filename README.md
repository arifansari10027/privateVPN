Test out my vpn by installing client side OpenVPN App 

<a href = "https://openvpn.net/community-downloads/">Download OpenVPN</a> 

Download the config file <a href = "https://github.com/arifansari10027/privateVPN/blob/1a4e1426c4caf1a88c76beeef9ad3e87650d50dd/profile-userlocked-test.ovpn">Click here</a>

This will automatically setup your custom made VPN which I have made 


<br><br>







This is a tutorial on how you can setup your own VPN


Step 1 - Sign up in linode.com 

Step 2- Go to marketplace and select OpenVPN

Step 3 - Configure it, create password of your own

Step 4 - Launch it

A new window will open and it will ask to login. Enter username as 'root' and password as which you created.

You can see your Public IP and SSH Adress in the main dashboard

Now, copy the SSH Adress and paste it into terminal, it will ask for your login crediantials

You will get a randomly generated password.

Now, Copy the public IP and paste into browser https://XXX.XXX.XXX.XXX:943/admin

This will open the admin panel, write username as 'openvpn' and password which you got from terminal.

This will open the admin panel and then now you can add new user and configure according to you
