# Salesforce_Opportunity_Example

Creating a Salesforce opportunity and adding line items to this Opportunity

This code will NOT run as is, I deleted the confidential information.
Through Python simple_salesforce a connection to SF is established.
login.json file has to be added. 
{
    "login": {
        "username": "your_user_name",
        "password": "your_password",
        "token": "the_generated_token" #please refer to SF documentation
    }
}

In my case I upload a csv file after converting several items to Salesforce format.

The data should be in json format. I think it should be clear from the code snippets.
