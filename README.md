### Run the server ###
- Install the dependencies
```node
npm install

APP_ID=ca123xxxxxx
APP_CERTIFICATE=12za123xxxxxx
```
- Start the service
```node
npm start
```

## Endpoints ##


### RTC Token ###
The `rtc` token endpoint requires a `tokentype` (uid || userAccount), `channelName`, and the user's `uid` (type varies based on `tokentype`). 
`(optional)` Pass an integer to represent the token lifetime in seconds.

**endpoint structure** 
```
/rtc/:channelName/:role/:tokentype/:uid/?expiry=
```

response:
``` 
{"rtcToken":" "} 
```

response:
``` 
{
  "rtcToken":" ",
  "rtmToken":" " 
} 
```
