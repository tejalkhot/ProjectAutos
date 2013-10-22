ProjectAutos
============

Android class project

API Calls
=========

Note: You can append format=json to all queries.

All categories of vehicles:

http://autos.query.yahoo.com:4080/v1/public/yql?q=select%20*%20from%20autos.categories

All new vehicle makes:

http://autos.query.yahoo.com:4080/v1/public/yql?q=SELECT%20*%20FROM%20autos.makes%20WHERE%20isNew='1'%20AND%20lang='en-US'

All new vehicle models given a make: 

http://autos.query.yahoo.com:4080/v1/public/yql?q=SELECT%20*%20FROM%20autos.models%20WHERE%20makeId='bmw'%20AND%20isNew='1'%20AND%20lang='en-US'

All used bmw cars(Note count and offset can also be specified):

http://autos.query.yahoo.com:4080/v1/public/yql?q=select%20*%20from%20autos.usedcars%20where%20make='bmw'

Details on a specific listing:

http://autos.query.yahoo.com:4080/v1/public/yql?q=select%20*%20from%20autos.usedcars%20where%20listingId=%22cars02-26282976%22


