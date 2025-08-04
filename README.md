# Databricks-to-Salesforce-Data-Cloud-Connector

Step 1: Create a Service Principal
Log in to your Databricks Workspace and navigate to the Admin Settings page by clicking your email in the bottom-left corner and selecting "Admin Settings".

Go to the Identity and access tab and click on Service principals.

Click the Add service principal button.

Give your Service Principal a descriptive name, for example, Salesforce Data Cloud Connector, and click Add.

Step 2: Get the Client ID
The Client ID is the unique identifier for the Service Principal you just created.

After creating the service principal, you will be taken back to the list. Click on the name of the service principal you just created (e.g., Salesforce Data Cloud Connector).

On the configuration page for the service principal, you will see a field labeled Application ID. This is your Client ID.

Copy this Application ID value. You will paste this into the "Client Id" field in Salesforce.

Step 3: Generate the Client Secret
The Client Secret is like a password for your Service Principal.

While still on the configuration page for your service principal, scroll down to the OAuth secrets section.

Click the Generate secret button.

Crucial Step: A dialog box will appear displaying your new secret. You must copy this secret now and store it in a secure location. You will not be able to see this value again after you close this window.

This generated value is your Client Secret. You will paste this into the "Client Secret" field in Salesforce.
