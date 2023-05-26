## Google Calendar API OAuth 2.0 for Web Server Applications Integration - Django Rest Framework


For run this project on a local machine: 

```sh
pip install - r requirements.txt
```

- Endpoint:
```
/rest/v1/calendar/init/ -> GoogleCalendarInitView()
```
This view should start step 1 of the OAuth. Which will prompt user for his/her credentials

```
/rest/v1/calendar/redirect/ -> GoogleCalendarRedirectView()
```
