Information About REST

REST has many methods, 5 of them are used extensively method.

POST (create):
Here URL will have entity type (say protection domain) and body will have values (say name of PD)

PUT(Create or replace): 
This will have entity type and its id in URL, 
The field to be modified will be mentioned in Body.

PATCH(update):
Don't know much

DELETE:
The url will have both entity type and its ID, and that will be deleted.

OPTIONS:
Used to get the supported operations on a resource.

HTTP resposes
100 series -> Information Responses
200 series -> Success  (201 created)
300 series -> Redirection
400 series -> Client Error (404 resource not found)
500 series -> Server Error (500 internal server error)
