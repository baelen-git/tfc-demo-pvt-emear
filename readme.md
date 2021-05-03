# CLEAN UP
1. Destroy and Delete your TFC Workspace
2. Delete your Intersight TFC Target and Agents
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
4. Go to Intersight and Setup TFC Cloud Agent

5. configure - Variables
```
vsphere_password = Demo123!
vsphere_user = "baelen@vsphere.local"
vsphere_server = "10.61.124.6"
```

5. Queue plan manually

6. Configure - Team Access
```
Infra Admins -> Admin
Application Team -> Plan
```

7. Show the Run and the State 

8. Add Sentinel and Kick off a new plan

9. Show the API & Documentation

10. Done!
