# nest api 
Connect to nest devices API with Python to get some infromation from Nest thermostat

Controlling a Google Nest Devices
Google recently released its Device Access API. 
This code is to show how to access and this API to get some information from Google Nest thermostat.
the sample output of the api is in nest_output.json my personal information is masked in the file with "*"

Get started with Google documentation:
1) First of all you need to register and pay 5 US$ (non-refundable fee) per account.
Registration consists of the acceptance of the Google API and Device Access Sandbox Terms of Service, along with a one-time, non-refundable fee (US$5) per account.

You can resgiter from here:
https://developers.google.com/nest/device-access/registration

the other useful link lsited below:

https://developers.google.com/nest/device-access/get-started
https://developers.google.com/nest/device-access/authorize
https://developers.google.com/nest/device-access/use-the-api
https://developers.google.com/nest/device-access/api/thermostat
https://console.nest.google.com/device-access/
https://console.developers.google.com/

Gather all requirements
It’s tempting to begin creating a Device Access project right away, but I found out that it is probably easier to get all the necessary prerequisites first. 
Before you can start coding you should follow these steps:

2) Create a Google Cloud Console project at console.cloud.google.com
In first page just define a name for your project , after create you can find your proiect id in next page.

3) Create Cloud Console oAuth 2.0 credentials
4) Set a redirect URI
5) Turn on the Smart Device Access API
6) Create a Device Access project at console.nest.google.com

After creating an OAuth 2.0 client ID and a Device Access project you will have these values:

A project ID. You can find this in your Device Access console. (https://console.nest.google.com/device-access/)
A client ID. You can find this with your OAuth credentials.
A client secret. You can find this with your OAuth credentials.
A redirect URI. This URI can be almost any URL you want, as long as this URL matches a URI that is entered as an authorized redirect URI in your Cloud Console project. 