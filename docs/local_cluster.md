Install kind
Create kind cluster
Create ServiceAccount and add proper IAM permissions
Create and Download service account key file 
Get the Base64 encoded key file contents and create a secret in K8s
Update the YAML files for each app with the Project_ID, App_Creds, Mount points
Apply the yaml files and see them working
