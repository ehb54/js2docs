# Setting up openrc.sh 

####<span style="color:red"> File copied over from JS1 - Make modifications for JS2</span> 
Jetstream has two clouds:  the IU cloud and the TACC cloud; each cloud has one domain, the 'TACC' domain.  API users will only be interacting with one cloud at a time.  Transferring entities such as images and volumes from one domain to the other requires intervention by systems personnel.  To request these services email help@xsede.org.
When using the 'TACC' domain, the username and password in the openrc.sh file are the same login credentials that would be used to access any of TACC's resources.  For assistance with TACC login credentials, visit [password reset] (https://portal.tacc.utexas.edu/password-reset/-/password/request-reset).


---
**IU cloud, TACC domain**
{: .note}

***TACC domain*** <br>  
>export OS_PROJECT_DOMAIN_NAME=tacc<br>
>export OS_USER_DOMAIN_NAME=tacc<br>
>export OS_PROJECT_NAME=TG_your_xsede_project_name<br>
>export OS_USERNAME=your_tacc_username<br>
>export OS_PASSWORD=your_tacc_password<br>
>export OS_AUTH_URL=*CONTACT HELP@XSEDE.ORG* for the available endpoint URL<br>
>export OS_IDENTITY_API_VERSION=3 <br> 

**TACC cloud, TACC domain**
{: .note}

***TACC domain*** <br>  
>export OS_PROJECT_DOMAIN_NAME=tacc<br>
>export OS_USER_DOMAIN_NAME=tacc<br>
>export OS_PROJECT_NAME=TG_your_xsede_project_name<br>
>export OS_USERNAME=your_tacc_username<br>
>export OS_PASSWORD=your_tacc_password<br>
>export OS_AUTH_URL=*CONTACT HELP@XSEDE.ORG* for the available endpoint URL<br>
>export OS_IDENTITY_API_VERSION=3<br>
---

### Using the Horizon dashboard to generate openrc.sh

1. Login to Horizon: <br>
>IU: https://iu.jetstream-cloud.org/dashboard<br>
>TACC: https://tacc.jetstream-cloud.org/dashboard<br>
>Domain: TACC
>User Name: *your TACC username*
>Password: *your TACC password*

2. If you are on more than one allocation, select the project (XSEDE allocation) by clicking where it says "tacc · TG-xxxxxxxx · RegionOne" and choose the appropriate allocation. 
3. Click on your username in the upper right hand corner
4: Click on Download OpenStack RC File v3 
The password is not stored in the script. This openrc.sh file will prompt for a password when sourced.
Note: To select an active project prior to generating openrc.sh, click on Identity (left hand side) to see a list of your projects.