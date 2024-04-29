# cloud-2.6-submit

IAM User: leon-temp-user


![2024-04-29-23-17-48-image](https://github.com/cheongjh/cloud-2.6-submit/assets/15931746/d685fd4a-ced4-415a-82cf-923dc59a57b1)

```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "ec2:RunInstances",
                "ec2:DescribeInstances",
                "ec2:TerminateInstances"
            ],
            "Resource": "arn:aws:ec2:*:*:instance/*"
        },
        {
            "Effect": "Allow",
            "Action": [
                "s3:CreateBucket",
                "s3:ListAllMyBuckets",
                "s3:ListBucket"
            ],
            "Resource": [
                "arn:aws:s3:::*"
            ]
        },
        {
            "Effect": "Allow",
            "Action": [
                "rds:DescribeDBInstances"
            ],
            "Resource": "*"
        }
    ]
}
```

![2024-04-29-23-18-50-image](https://github.com/cheongjh/cloud-2.6-submit/assets/15931746/b4771b25-1c56-49c6-99c5-137d464db509)

![image](https://github.com/cheongjh/cloud-2.6-submit/assets/15931746/5c16b574-5b78-44f3-a791-78e2d86be7e8)
