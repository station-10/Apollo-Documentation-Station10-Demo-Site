# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Detected",
    "user": {
        "custKey": "<custKey>",
        "customerDetails": {
            "SUID": "<SUID>"
        },
        "loginStatus": "<loginStatus>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|SUID|string|Captures the user ID based on a cookie.||||||||
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||




