# Ec2--project
Steps of the project
1. Launch Ec2 Instance:
   Go to AWS Management Console and navigate to Ec2 Dashboard
   click on Launch Instance.
   
2. Select Application and OS image (AMI):
   Choose Amazon Machine Image(AMI) with Windows as the Operating system.

3. ![Create Key pair](./create_keypair.png)
   Create new Key Pair and Download the file and store it securly, as it is required to decrypt the password.

4. Launch the Instance:
   ![Click Launch](./Instance_Launch.png)
   ![Wait for instance to initialize until the Status Check show 2/2 check passed to connect](./statuscheck.png)

6. Connect to Instance via RDP:
   Click connect and select RDP client.
   Download Desktop File - Click on Get Password and upload keypair file to decrypt the Windows Administrator Password.

7. ![Decrypt Password](./decrypt_pass.png)

8. RDP Connection:
   ![Enter the Decrypted Password and Click connect](./instance_connect.png)

9. Windows Screen out in the cloud:
   ![Windows environment accessible to host or deploy](./windows.jpeg)
