# AZterraform
AZURE TERRAFORM 

Terraform + AZURE :
TERRAFORM : Terraform is an open-source Infrastructure as Code (IaC) tool developed by HashiCorp. It allows users to define, provision, and manage infrastructure resources (like servers, storage, and networking) across various cloud providers and on-premises environments using a declarative configuration language called HCL (HashiCorp Configuration Language) 

 # INFRA AS A CODE :
         
 TOOLS IAAC : TERRAFORM , PULUMI,AZURE ARM,AWS CLOUD FORMATION

 INFRASTRUTURE : TO PROVISION INFRASTURTURE < SERVERS , RESOURECES ETC.....

  3 TIER ACRHITECTURE :

  WEB SERVERS  + APP SERVERS  + DATA BASE 

AND Load Balencer for application and web, we can create by thru terraform. and we can reuse same code using in different environments. the values are changed accroding to enivironment.

# EC2 SERVERS -->AZURE V M
**CHALLENGES :**
 TIME
 PEOPLE
 COST
 REPETITIVE
 HUMAN ERRORS
 INSECURE 
 
**How terraform helps:**

 Automate infrastructure,
 save cost
 save security
 saving time
 write once deploy many times 
 git - source code management, so we can control and secure code.
 Easy.

- .tf  --> saving a file

 terraform init : initialize terraform 
 terraform validate : to validate the code
 plan : to show the out put for our code, before apply. <dry run>
 terraform apply : finally make changes the infra, and deploy the our resources.
 terraform destroy : to clean up our not used resources.

Main commands:
 - init           : Prepare your working directory for other commands
 - validate       : Check whether the configuration is valid
 - plan           : Show changes required by the current configuration
 - apply          : Create or update infrastructure
 - destroy        : Destroy previously-created infrastructure

All other commands:
 - console       : Try Terraform expressions at an interactive command prompt
 - fmt           : Reformat your configuration in the standard style
 - force-unlock  : Release a stuck lock on the current workspace
 - get           : Install or upgrade remote Terraform modules
 - graph         : Generate a Graphviz graph of the steps in an operation
 - import        : Associate existing infrastructure with a Terraform resource
 - login         : Obtain and save credentials for a remote host
-  logout        : Remove locally-stored credentials for a remote host
-  metadata      : Metadata related commands
- output         : Show output values from your root module
-  providers     : Show the providers required for this configuration
-  refresh       : Update the state to match remote systems
-  show          : Show the current state or a saved plan
-  state         : Advanced state management
- taint          : Mark a resource instance as not fully functional
-  test          : Execute integration tests for Terraform modules
-  untaint       : Remove the 'tainted' state from a resource instance
-  version       : Show the current Terraform version
- workspace      : Workspace management