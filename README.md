# Creating-Ec2-Instance & Login using Mobaexterm
Steps To Create Ec2 Instance

1. Login To AWS Consoul Either By Root User Or iam User
2. Go To Services On the top left courner
3. Select Ec2
4. create a name for the instance
5. select the OS which user asked for.
6. select the instance configuration as needed 
7. select the existing keypair or create a new pair if not there .
8. (if any more configurations needed add them based on the user requirements) Optional
9. click on launch instance

# Login Using Mobaexterm


1. open Mobaexterm
2. on the top right hand side select sessions, new session
3. select SSH 
4. Enter the Public IP eddress of the ec2 instance
5. Enter the username same as in the AWS Counsoul
6. Click on advanced SSH Setting in that brouse our keypair in .pem file format 
7. select Ok now you are successfully loged into the aws ec2 instance..
