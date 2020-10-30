# golden-dataset
Study .json file for data from the LLZ study

## Study Summary

## Variables Measured

## Graph API Access

You can access the Graph API with the following credentials. Please add your email and password, I have added all of you as admins to the Cluster for the data. 

```
http.post({
  "url": "https://eu-west-1.aws.realm.mongodb.com/api/client/v2.0/app/adsata-golden-kfkva/graphql",
  "headers": {
    "email": "<User's Email Address>",
    "password": "<User's Password>",
  },
  "body": '{"query":"query  **ADD TYPE** {\n  **SOMETYPE** {\n    **SOMETYPE**\n    **SOMETYPE**\n  }\n}"}'
})
```


## Schema
