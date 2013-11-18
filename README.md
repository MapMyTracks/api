Map My Tracks API
===
Map My Tracks provides a simple interface that allows developers to access and update their activity data. You can use this API to make your own widgets or applications that seamlessly integrate Map My Tracks with other services.

Overview
---
The API consists of a number of services which are accessed by sending a HTTP POST to the Map My Tracks API URL at <code>http://www.mapmytracks.com/api/</code>. All requests require basic HTTP authentication using a valid Map My Tracks username and password. All API requests will be assigned to the user's account. The API responds with an XML formatted message. The content of this message will be dependent on the type of request that was made.

**Data retrieval**
* [Get activities](services/get_activities.md)
* [Get activity](services/get_activity.md)

**Tracking**
* [Start activity](services/start_activity.md)
* [Update activity](services/update_activity.md)
* [Stop activity](services/stop_activity.md)
* [Get time](services/get_time.md)

**Data input**
* [Upload activity](services/upload_activity.md)
