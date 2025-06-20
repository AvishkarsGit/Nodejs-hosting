## Deploying Nodejs, MongoDB project on Hostinger vps hosting

- Prepare the vps environment
- Setup MongoDB Atlas on vps
- Deploy your node js and express app

### 1. Prepare the vps environment

#### Buy vps hosting : [Get Hosting](https://www.hostinger.com/in/vps-hosting)

#### Login into vps terminal

```
ssh root@<your_vps_ip_address>
```

- ##### hint: After pasting this command, you will have to enter password.

#### Upgrade and update your system with latest required configuration

```
sudo apt update
```

```
sudo apt upgrade -y
```

#### Install node js and npm ( if not pre-installed)

```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo bash -
```

```
sudo apt-get install -y nodejs
```

- ##### note: npm will install automatically when you'll install node js

#### install git

```
sudo apt install -y git
```

### 2. Setup MongoDB Atlas on vps

#### Go to VPS panel in hostinger

#### Copy your vps Ip address.

![alt text](image-3.png)


#### Login into mongodb atlas

#### Go to Network Access tab

![alt text](image.png)

#### Click on 'ADD IP ADDRESS' and paste your vps IP address (comment is optional)

![alt text](image-1.png)

### 3. Deploying the Express and Node.js Backend

#### You are in the terminal now
####