# Setup the VPS Server
## Sign in DigitalOcean
DigitalOcean is our VPS of choice. First, we need to create an account.
1. Create a profile at [DigitalOcean](https://www.digitalocean.com/try/developer-brand?utm_campaign=amer_brand_kw_en_cpc&utm_adgroup=digitalocean_exact_exact&_keyword=digitalocean&_device=c&_adposition=&utm_content=conversion&utm_medium=cpc&utm_source=google&gclid=Cj0KCQjw-JyUBhCuARIsANUqQ_JRBXlK7yRkm53Bi9aVY71WVapTh3yNNCjzfUifL8i6LrWCruvSZfgaAvCTEALw_wcB) website;
2. Choose the propreties that suit you the most;
3. When you will be able to access it, go to the project section to your left;
4. Create a new project in "+ New project".

## Create droplet
1. When you have created a new project, choose "Create" at the top of the page;
2. Choose "Droplets". In paranteses will be listed recommended option:
  - Choose distribution (Debian);
  - Choose plan (Basic, Regular with SSD, $5/mo);
  - Choose a datacenter region (the is the closest to your location);
  - Authentication.
3. The droplet has been created. You can view the IP address on your project's main page.

## Log in your newly created VPS service
1. Open Terminal;
2. Update and upgrade your system by running ````$ sudo apt update```` and then ````$ sudo apt update````;
3. Enter the line ````$ sudo ssh root@192.168.0.1````, where instead of ````192.168.0.1```` you input the IP address of your newly created droplet;
4. Now you are in!

## Create SSH key
SSH key are needed for a secure access to our VPS server.
1. In Terminal enter ````$ ssh-keygen````. This will generate a SSH key;
2. The key will be automatically saved in '/home/user/.ssh/id_rsa' directory. It may be changed;
3. Next, enter  ````$ ssh-keygen````


## Set up web server
1. In terminal, insert the
