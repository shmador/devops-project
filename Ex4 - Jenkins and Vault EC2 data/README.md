# How to Use - Vault Setup with Jenkins

1. Run the following command to set up Vault:

```bash
./vault_setup <AWS_ACCESS_KEY_ID> <AWS_SECRET_ACCESS_KEY>
```

2. Go to `localhost:8080` and create a new pipeline job using the `Jenkinsfile` provided in this directory

3. Check the output log of the pipeline job  
   You should see all the instances associated with the AWS credentials in the `il-central-1` region

This setup demonstrates how to use secret data in Jenkins with HashiCorp Vault

