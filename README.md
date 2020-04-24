==== Query
  curl -i -X GET \
   "https://graph.facebook.com/v6.0/me?fields=id%2Cname&access_token=<access token sanitized>"
==== Access Token Info
  {
    "perms": [
      "public_profile"
    ],
    "user_id": 2600143783542449,
    "app_id": 1532473970267574
  }
==== Parameters
- Query Parameters


  {
    "fields": "id,name"
  }
- POST Parameters


  {}
==== Response
  {
    "id": "2600143783542449",
    "name": "عبدالله بن سلمان السحاري"
  }
==== Debug Information from Graph API Explorer
- https://developers.facebook.com/tools/explorer/1532473970267574/?method=GET&path=me%3Ffields%3Did%2Cname&version=v6.0# -1
