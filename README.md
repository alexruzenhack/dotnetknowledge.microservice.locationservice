# dotnetknowledge.microservice.locationservice
Service to keep a historical record of team member locations 

*REST API for the location service*

| Resource | Method |	Description |
|----------|--------|-------------|
| /locations/{memberID}/latest |	GET |	Retrieves the most current location of a member |
| /locations/{memberID} |	POST |	Adds a location record to a member |
| /locations/{memberID} |	GET |	Retrieves the location history of a member |
