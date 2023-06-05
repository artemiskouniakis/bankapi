#Activate key pair
chmod 400 ~/Downloads/bankapi.pem

#Connect to cloud virtual machine of linux
ssh -i ~/Downloads/bankapi.pem ubuntu@ec2-16-171-25-228.eu-north-1.compute.amazonaws.com