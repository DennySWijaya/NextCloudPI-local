# NextCloudPI-local
Just a private cloud storage at home, purposed like a NAS. Using this Raspberry Pi 400 that's collecting dust at home
 

#### 1. Prerequisites 

- **Raspberry Pi**: Any model will work, but a Raspberry Pi 4 is recommended for better performance.
     - Used Raspberry Pi 400.

- **SD Card**: Minimum 16GB, but 32GB or larger is recommended.
     - Used 64GB.

- **Computer**: To flash the NextCloudPi image to the SD card. 

- **Internet Connection**: For downloading the image and updates.

- **Hard Disk Drive (HDD)**
     - Used a Laptop HDD Toshiba 2,5" combined with 2,5" SATA to USB 3.0 Adapter


  
#### 2. Download NextCloudPi Image 

- Visit the [NextCloudPi GitHub releases page](https://help.nextcloud.com/t/how-to-install-nextcloudpi/126308) and download the latest image matching Raspberry Pi 4 model. 

 

#### 3. Flash the Image to the SD Card 

- Download and install **BalenaEtcher** from its official website. 

- Open BalenaEtcher, select the downloaded NextCloudPi image, and the prepared SD card. 

- Click "Flash!" to write the image to the SD card. 

 

#### 4. Insert SD Card into Raspberry Pi 

- Insert the SD card into Raspberry Pi 400 and power it on. 

- Wait for the initial setup to complete, may take a few minutes. 

 

#### 5. Access the Web Interface 

- Open a web browser and enter `https://nextcloudpi.local:4443` or Raspberry Pi 400's IP Address followed by `:4443`. 

- You may see a security warning about a self-signed certificate. Click "Advanced" and then "Proceed" to continue. 

 

#### 6. Complete the Setup Wizard 

- Follow the on-screen instructions to complete the setup wizard. 

- Create an admin password for NextCloudPi and a login password for the NextCloud instance. 

 

#### 7. Configure NextCloudPi 

- Access the NextCloudPi admin interface at `https://nextcloudpi:4443`. 

- Use the admin panel to configure settings such as storage locations, user accounts, and security options.

     - Enable nc-datadir to move storage from SD Card to HDD.
     - Enable nc-prettyURL, can hide PHP process in the address bar to some extent.
     - Enable nc-static-ip, add with prepared IP Address



#### 8. Create Users (and Groups)

- Allow other users to access Nextcloud instance.
     - Login using Admin panel, then click profile on the top right, and choose Account
     - To make a new account, click 'New Account' and input the new account informations, then click 'Add new account' to ready the account.
     - To make a new group, click the '+' icon beside Groups, set the group name, and press enter or click arrow icon next to the text box.


- Groups allows multiple users to share the same resource in the same group.
  
- Sharing folder an still be done by allowing sharing certain folders to certain users.
 
