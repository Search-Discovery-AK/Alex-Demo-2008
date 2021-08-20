# Accommodation Booking Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Accommodation Booking Completed",
    "booking": {
        "roomList": [
            {
                "location": {
                    "locationId": "<locationId>"
                }
            }
        ],
        "total": {
            "currency": "<currency>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|currency|string|Currency of the payment for the booking. ISO 4217 \(3 character alpha\), uppercase |USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|locationId|string|Unique Identifier of a Location. |155, 65588, 987764448|||||||
