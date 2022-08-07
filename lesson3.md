#### Tagging Resources with compliance checks

    
    50 tags per resources

1 Strategies:

    project:Webiste
    project:DR
    project:NewInisitave

    Application:Apache
    Tier:Public
    Tier:Backend

You can enforce the use of tags, using policies in IAM.

```json

{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "CheckTag",
      "Effect": "Deny",
      "Action": "ec2:RunInstances",
        "Resource": "*",
        "Condition": {
          "Null": {
            "aws:RequestTag/costCenter": "true"
          }
        }
    }
  ]
}

```
