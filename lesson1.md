#### AWS Account Basic

- Root Account:
 
    1- Consider using a distribution list email.
    
    2- Use email aliases.

    3- Root email can only be changed by the **root**user.
    
    4- If you close the account,that root email could no be used again.

    5- When is required to use root account :
    
        - Create a Cloudfront key pair.
        - Enable longer EC2 resources IDS.
        - Configure S3 bucket for MFA delete.
        - Edit/Delete S3 bucket policy with invalid VPC ID or VPC
        - Request removal of port 25 throttle on EC2 instance.
        - Find AWS canonical account ID.
        - Enable recive billing alerts.

