This is a result of open record request work to try and map "poll_place_name" (as opposed to "polling_place_name") to "poll place id". Recall that the SOS reporting at: 
https://earlyvoting.texas-election.com/Elections/getElectionEVDates.do

doesn't do a good job of this mapping. So, the "Official Polling Place Information by County" report gives you a list of polling locations with addresses using the field name "poll place name". The report under "Official Election Day Turnout by County" gives you a report with the count of how many people voted on election day at the election day polling locations, but the report doesn't give you a "poll place name" field. Instead if gives you a "poll place id" field and a field called "polling place name" which is in fact the field labeled “POLL PLACE LOCATION (BUILDING/OFFICE NAME)” in SOS's TEAMS system.

So, this data was my attempt, for large counties, to map "poll place id" to "poll place name".
