HW Class 7 (09/16/25)

Instructions for Creating an EC2 instance:

1. Search bar in AWS console "EC2", then proceed to security groups. Create a security group, give it a name, and copy the name into the description. Leave the default VPC as is.

2. Add inbound rules for type pick HTTP and for source pick the Anywhere IPv4 option. DO NOT TOUCH THE OUTBOUND RULES! Add tags if you want, then proceed to creating a security group. 		

3. Next, go to Instances in the EC2 left pane. Proceed to launching instances, create a name (copy the same name from the security groups).

4. Leave the Application and OS Images as the default from the quick start column {Amazon Linux}. Leave your instance type as is. For the Key pair, select without the key pair. 	

5. For network settings, select the existing security group and choose the name you created before.	

6. Go to Advanced Details and go to user data, input the start script from Theo's GitHub account (bmc4/ec2script) after launching the instance and waiting for about one minute for it to complete loading fully. 	

7. Click your Instance ID, then copy your Public DNS. Next, open a new browser tab and type in http://*then your EC2 instance link*. Once the web page shows your details, you can close it.

8. Go back to your Instance page and click the instance state tab on the top right, and terminate the instance. It should take about a minute to fully terminate. 	# 09.16.25
