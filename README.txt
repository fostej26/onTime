onTime is a student scheduling aid that retrieves events from a user's google calendar and sends an
SMS message 30 minutes before the estimated time of departure for your event. The time of departure
is calculated in real time using google maps traffic data. 

Use:

1. install with pip: googlemaps, twilio, datetime, google-auth, google-auth-oauthlib, google-auth-httplib2

2. Setup a google cloud developer account and create a new project

3. Enable Maps and Calendar APIS for created project. For the maps API, retreive the API key. For the
calendar API, retrieve the API key, then create credentials and save them as a .json file. Then
create an oauth2 account and enable all scopes of the calendar API (select all).

4. Create a twilio account and create a twilio phone number. Get account credentials (sid,token,phone)

5. Replace all named parameters in lines 21-27, 109, 150-152. 

6. Run code and enter starting location. Leave running for as long as desired.

