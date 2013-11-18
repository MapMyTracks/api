Upload activity
====
Upload an activity in it's entirety, in GPX format

Parameters
---
`request`
The request identifier. To perform this API request, set this to 'upload_activity'.

`gpx_file`
A GPX file formatted representation of the activity

`status`
Indicates if this activity is to be public or privately visible. Possible values are "public" and "private".

`description`
The request identifier. To perform this API request, set this to 'get_time'.

`activity`
The activity type. Possible values are "running", "cycling", "mountain biking", "sailing", "walking", "hiking", "driving", "motor racing", "off road driving", "motorcycling", "enduro", "skiing", "cross country skiing", "canoeing", "kayaking", "sea kayaking", "stand up paddle boarding", "rowing", "windsurfing", "kiteboarding", "orienteering", "mountaineering", "skating", "skateboarding", "longboarding", "horse riding", "hang gliding", "gliding", "flying", "snowboarding", "paragliding", "hiking", "hot air ballooning", "stand up paddle boarding" and "nordic walking".

Returns an XML formatted replay indicating success or failure

Example POST
---
(gpx_file has been truncated for clarity)

```
request=upload_activity&gpx_file=<?xml version="1.0" encoding="ISO-8859-1" standalone="yes"?>
             <?xml-stylesheet type="text/xsl" href="details.xsl"?>
                <gpx version="1.0" creator=...
status=public&
description=My weekend run&
activity=running
```


Returns, if successful.

```
<?xml version="1.0" encoding="UTF-8"?>
<message>
	<type>success</type>
</message>
```
