##Login to reteive API KEY:
    https://earthexplorer.usgs.gov/inventory/json/v/1.4.1/login?
      * For POST request:
          body -> x-www-formurlencoded ->
	      * KEY: jsonRequest
	      * VALUE: {
                   "username": "<USERNAME>",
                   "password": "<PASSWORD>",
                   "authType": "EROS",
                   "catalogId": "EE"
                }
##Datasets Search (Partial):
    https://earthexplorer.usgs.gov/inventory/json/v/1.4.1/datasets?jsonRequest={"datasetName": "L8", "spatialFilter": {"filterType": "mbr","lowerLeft": {"latitude":16.2991,"longitude": 80.8594},"upperRight": {"latitude": 16.6362,"longitude": 81.5625}},"temporalFilter": {"startDate": "YYYY-MM-DD","endDate": "YYYY-MM-DD"},"apiKey": "<API KEY HERE>"}

