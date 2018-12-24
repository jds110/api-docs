# Authentication
When making a request, you must include your account ID from within stream elements. Find your Account ID <a href="https://streamelements.com/dashboard/account/channels">here</a>.

Here is an example request from <a href="http://getpostman.com"> PostMan</a>: https://api.streamelements.com/kappa/v2/channels/LIRIK?token=<account_id>

Example reponse:
```json
  {
    "profile": {
        "social": {
            "youtube": "https://youtube.com/channel/UCdwlZJo83T3aNZ23vU_DvTw"
        },
        "headerImage": "https://cdn.streamelements.com/static/user/profile_header_default.png",
        "title": "lirik's profile"
    },
    "provider": "youtube",
    "_id": "5b63e96c8c5c59361a32c52e",
    "providerId": "UCdwlZJo83T3aNZ23vU_DvTw",
    "username": "lirik",
    "alias": "lirik",
    "avatar": "https://yt3.ggpht.com/-xj-gcpzhhUY/AAAAAAAAAAI/AAAAAAAAAAA/R0zRL1zeNpI/s240-c-k-no-mo-rj-c0xffffff/photo.jpg",
    "displayName": "lirik",
    "inactive": false
}
 ```
