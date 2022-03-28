# AWSCognitoUserPools


This app need three services
1. AWS Cognito
2. S3 bucket
3. IAM service

In Index.html update the below key components (line 48 to 53)
<User Pool ID>
<App Client ID>
<Region>
<Identity Pool ID>
  
** Upload this index.html and script folder in S3 bucket and make this files as public
  
  
Access the endpoint which is created in AWS Cognito Userpool  
  

  
  
  *** Place below JSON in S3 Cors
  [
    {
        "AllowedHeaders": [
            "*"
        ],
        "AllowedMethods": [
            "GET",
            "PUT",
            "POST",
            "DELETE"
        ],
        "AllowedOrigins": [
            "*"
        ],
        "ExposeHeaders": []
    } 
]
