# golden-dataset
Here you can find data from Daniel's eyetracking study at the LLZ. This data will form the base of the adsata "golden" dataset. Meaning we can reliably use this data for testing new features, metrics, and visualisations. 

You can access the data in two ways:

- adsata-godlen.json file for all the data --> Attched to this repo
- Access with POST reguest to a Graph API --> see bwlo for access details and the schem.graphql file for the Graph schema.

## Study Summary

## Variables Measured

## Graph API Access

You can access the Graph API with the following credentials. Please add your email and password, I have added all of you as admins to the Cluster for the data. 

You can query this data in GraphQL([https://graphql.org]).

```curl
http.post({
  "url": "https://eu-west-1.aws.realm.mongodb.com/api/client/v2.0/app/adsata-golden-kfkva/graphql",
  "headers": {
    "email": "<User's Email Address>",
    "password": "<User's Password>",
  },
  "body": '{"query":"query  **ADD TYPE** {\n  **SOMETYPE** {\n    **SOMETYPE**\n    **SOMETYPE**\n  }\n}"}'
})
```


## Graph Schema

See the **schema.hraphql** file for the graph schema.

