# Event-Driven-Lambda
This is a Python/Lambda project I built using the materials I got from a aws course from https://learn.cantrill.io/. I built this out before taking my aws solutions architect certification so I could get hands on experience.

This project consits of: 
- Creating two EC2 Instances
- Creating a Python script that starts and stops EC2 instances using instance ID
- Creating another Python script which “protects” an EC2 Instance. So when an EC2 Instance stops the script will recognize this and start another EC2 Instance
- Uploading the script to AWS Lambda
