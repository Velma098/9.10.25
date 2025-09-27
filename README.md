class7hw1

10 September 2025
Launching an ec2 instance:
The first step create new security group. Do Not touch default
Change inbound rules to (HTTP) Change source to (Anywhere-IPV4)
Tags (optional)
DO NOT TOUCH OUTBOUND RULES
Create security group
Click launch an instance
Skip keypair for now (Proceed without a keypair)
Select existing security group
Select advance detail (user data)
Paste the simple.sh
Launch instance
Wait a few minutes paste public dns in address bar with http://ec2-34-227-9-110.compute-1.amazonaws.com (example)
Tear down:
Check the instance box
Click instance state
Terminate (delete) instance
