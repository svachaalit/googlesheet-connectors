# googlesheet-connectors
This repo contains the sample code that can be used to automate the process of pulling the details of installbase of IO connectos

# Getting started
Prerequisite 
 - Developer account on [![N|Solid](https://integrator.io/images/favicon.ico) Integrator.io ](https://integrator.io/signin)
 - Have a connector on [ Integrator.io ](https://integrator.io/signin)
 - Google Sheets
 
 Once you have all the above, go to google sheet where you want to see information details from the connector.
 - Go to Google sheet menu
 - - Click ```tools > Script Editor```
 - - In the script editor, go to menu "Resources > Libraries..."
 - - Fill box "Add Library" with value ```MOxoBX79ENYSrsyIBPDlzGSkXlAB7Sf_4``` [This is the project id for library]
 - - Use latest version
 
 One this is done write a sample script with this code
 ```nodejs
 function myFunction() {
  ConnectorDetails.fillDetails()
}
```

Running this will populate the data in the sheet.

