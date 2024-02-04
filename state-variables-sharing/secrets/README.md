# Secrets
You can store your actions secrets for example to access AWS under setup/secrets/actions as shown in the image.
![setup a secret](img.png)

After you store the secret, it will be encrypted, and you will not be able to see it. The github job will decrypt the 
secret and get its value when it runs the workflow.
If you want to update the scret yaou can do that, but you can not view the exiting value.

![using secret example](img_1.png)




