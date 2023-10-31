# deccob
Analysing event data for Stuttgart

### Main Question to answer: Where in Stuttgart is agood place to go out at wednesdays?



## json data for one event

```json
{
    "id": "prinz.de/stuttgart/events/515144-gedenktag-fuer-die-verstorbenen-drogenabhaeng-1",
    "eventData": {
        "name": "Gedenktag für die verstorbenen Drogenabhängigen",
        "description": "Ab 12 Uhr hält der diesjährige Schirmherr Josha Frey eine Rede halten. Danach folgt ein Statement des JES-Bundesvorstands Roland Baur, als Vertretung der in der Selbsthilfe Engagierten Junkies, Ehemaligen und Substituierten. \n\nAb 13.00 Uhr sind Betroffene, Angehörige und Freunde zum “stillen Gedenken” in die Leonhardskirche eingeladen.\n\nIm Anschluss wird mit dem Aufstieg schwarzer Luftballons symbolisch der verstorbenen Drogenabhängigen gedacht und für die Lebenden ein Zeichen gesetzt.", 
        "sourceId": "515144", "url": "http://prinz.de/stuttgart/events/515144-gedenktag-fuer-die-verstorbenen-drogenabhaeng-1", 
        "startDate": "2015-07-21T12:00:00", 
        "endDate": null, 
        "doorTime": null, 
        "cancelled": false, 
        "location": {
            "sourceId": "97941", 
            "url": "http://prinz.de/stuttgart/locations/97941-karlsplatz/", 
            "name": "Karlsplatz", 
            "description": null, 
            "location": {
                "name": "Karlsplatz", 
                "address": {
                    "country": {
                        "shortName": null, 
                        "longName": null}, 
                    "region": null, 
                    "county": null, 
                    "city": "Stuttgart", 
                    "district": null, 
                    "postalCode": "", 
                    "street": "- -", 
                    "houseNumber": null, 
                    "coordinate": null, 
                    "addressDescription": null}, 
                "telephoneNumbers": null, 
                "emailAddresses": null, 
                "emailAddressesAsString": null, 
                "telephoneNumbersAsString": null, 
                "websites": null, 
                "websitesAsString": null, 
                "coordinate": {
                    "lat": 48.7754181, 
                    "lon": 9.1817588}, 
                "score": null, 
                "elasticsearchTimestamp": null, 
                "elasticsearchIndexTimestamp": null}, 
            "category": "stadtleben/special-events", 
            "phone": null, 
            "email": null, 
            "website": "http://www.aidshilfe-stuttgart.de/", 
            "facebook": null, 
            "twitter": null, 
            "wikipedia": null}, 
        "organizer": null, 
        "price": null, 
        "eventTyp": null, 
        "webpageEvent": null, 
        "facebookEvent": null, 
        "artists": null, 
        "sourceDate": "2015-09-17T10:29:52.5326587", 
        "ticket": null}, 
    "hostname": "prinz.de"}
```

### Reducing amount of data 
We are only interested in places that are open on Wednesdays or events which take place on Wednesday. It might be actually cool, to also set a date in the dashboard, and then we could recommend some special events that take place only once. 