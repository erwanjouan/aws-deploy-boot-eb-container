# aws-deploy-boot-eb-container

### Notes

- t2.micro instance type makes spring boot crash with OOM.
- EB maps application port (declared in conf) to 80 on EC2 instance, no need to configure listener to 8080