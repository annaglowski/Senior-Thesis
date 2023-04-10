This repository includes the python code for the computation of Anna Glowski's Senior Thesis. Each file is titled after the chapter of the Thesis in which it was used. The "Location Mapping" code was used to map the location of all activities for their respective chapters. For all Code, the Google Maps API key is removed. The user will need to access a key from the Google Maps API to rerun this code.

[Chapter 2] Data Collection and Calculation 
  - Data Collection: imports wait time data from Thrill Data, collects the location of each activity from Google Maps API
  - Data Calculation: calculates the walking distance between activities using the Google Maps Distance API (i.e. creates distance matrix for all formulations)
  
[Chapter 3] Initial Formulation of the TSP
  - Defines and formulates the initial TSP problem applied to Disneyland
  - take results of model and calculates walking distance, and maps the path on a map of the park
  
[Chapter 4] TSP with Time
  - Defines and reformulates the TSP problem applied to Disneyland with time
 - calculates walking distance of resulting route and maps the path on a map of the park
  
[Chapter 5] Complication One: Dining
  - Defines and formulates the model with the requirement that guests eat both lunch and dinner
  - calculates walking distance of resulting route, finds itinerary, and maps the path on a map of the park
 
[Chapter 6] Complication two: Prioritization of Rides with Multiple visits
  - Defines and formulates the model with the the ability to ride attractions more than once with a priority ranking
  - calculates total reward and walking distance of resulting route, finds itinerary, and maps the path on a map of the park
  
[Chapter 7] Complication three: Downtime
  - Defines and formulates the model with the the required downtime
  - calculates total reward and walking distance of resulting route, finds itinerary, and maps the path on a map of the park
