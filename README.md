# NextCloudPI-local
Just a private cloud storage at home, purposed like a NAS. Using this Raspberry Pi 400 that's collecting dust at home
 

#### 1. Prerequisites 

- **Raspberry Pi**: Any model will work, but a Raspberry Pi 4 is recommended for better performance. 

- **SD Card**: Minimum 16GB, but 32GB or larger is recommended. 

- **Computer**: To flash the NextCloudPi image to the SD card. 

- **Internet Connection**: For downloading the image and updates.


  
#### 2. Download NextCloudPi Image 

- Visit the [NextCloudPi GitHub releases page](https://help.nextcloud.com/t/how-to-install-nextcloudpi/126308) and download the latest image for your Raspberry Pi model. 

 

#### 3. Flash the Image to the SD Card 

- Download and install **BalenaEtcher** from its official website. 

- Open BalenaEtcher, select the downloaded NextCloudPi image, and your SD card. 

- Click "Flash!" to write the image to the SD card. 

 

#### 4. Insert SD Card into Raspberry Pi 

- Insert the SD card into your Raspberry Pi and power it on. 

- Wait for the initial setup to complete. This may take a few minutes. 

 

#### 5. Access the Web Interface 

- Open a web browser and enter `https://nextcloudpi.local:4443` or the IP address of your Raspberry Pi followed by `:4443`. 

- You may see a security warning about a self-signed certificate. Click "Advanced" and then "Proceed" to continue. 

 

#### 6. Complete the Setup Wizard 

- Follow the on-screen instructions to complete the setup wizard. 

- You will be prompted to create an admin password for NextCloudPi and a login password for your NextCloud instance. 

 

#### 7. Configure NextCloudPi 

- Access the NextCloudPi admin interface at `https://nextcloudpi:4443`. 

- Use the admin panel to configure settings such as storage locations, user accounts, and security options. 

 

#### 8. Make NextCloud Publicly Accessible (Optional) 

- If you want to access your NextCloud instance from outside your network, you'll need to set up port forwarding on your router and possibly use a Dynamic DNS service. 

- Follow the instructions in the NextCloudPi documentation to configure port forwarding and DNS settings. 

 

#### 9. Enable Remote Access 

- Ensure your Raspberry Pi is connected to the internet. 

- Set up port forwarding on your router to forward port 443 (HTTPS) to your Raspberry Pi's IP address. 

- Optionally, use a Dynamic DNS service to handle changing IP addresses. 

 

#### 10. Test Your Setup 

- Try accessing your NextCloud instance from another device outside your network to ensure everything is working correctly. 

 
