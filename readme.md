# SCRIPT

1. show the code
```
main.tf -> no vault, no remote backend
terraform.auto.tfvars -> all non sensitive variables
```
2. Create a new workspace from this repo

3. Configure - General Settings:
```
Remote Agent amslab
Auto Apply
```

4. configure - Variables
```
vsphere_password = Demo123!
```

5. Queue plan manually

6. Configure - Team Access
```
Infra Admins -> Admin
Application Team -> Plan
```

7. Show the Run and the State 

8. Show the API & Documentation
