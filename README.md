# optima-graphql

## Creating parameters to be used by the template
```
aws ssm put-parameter --name "/login_url" --value "your_url_login" --type "String"
aws ssm put-parameter --name "/api_url" --value "your_api_url" --type "String"
aws ssm put-parameter --name "/client_id" --value "your_client_id" --type "String"
aws ssm put-parameter --name "/client_secret" --value "your_client_secret" --type "String"
aws ssm put-parameter --name "/grant_type" --value "your_grant_type" --type "String"
```

