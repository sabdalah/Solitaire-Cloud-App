Safa Abdalah


The objective for this project was to take an open source application and create it into a Cloud Application
Currently the project Uses a CI/CD pipeline to Build and push a docker image to my personal Dockerhub Repo
Then, GithubActions will ssh into the EC2 instance created using Terraform IaC


Needs: 
dynamic IP fetch of ec2 instance (currently needs to be updated per instance in secrets due to troubleshooting)
Security with ec2


Link to see  a Demo of how it works:
https://youtu.be/Ti7bD071rZk

If you see any failed actions most likely I am updating the repo after I have run terraform destroy. Without the infrastructure there is failure. :D
