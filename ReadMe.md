			--- PUBLIC API INFOS -----

For this work we used python herepy 3.1.0 client API for geocoding and routing :
- https://pypi.org/project/herepy/
- https://github.com/abdullahselek/HerePy

hereby is a python version of HERE MAP API
Created a profile at https://developer.here.com/ and generated your API key from a REST application.

For more info please look documentation at https://herepy.readthedocs.io/_/downloads/en/stable/pdf/


          --- CODE EXPLANATION -----
The platform used is jypter notebook  6.0.1 with ipython 7.8.0 and python 3.7 on Ubuntu 18.04

the code is provided in the DistanceLocationTest.ipynb and it's structure as follow:

- GpsLocation class: creates a a GPS location Object when given a latitude and longitude values

- DlaPairLocations class : creates an object of pair of GPS Locations in the city of Douala. It has a method dla_distance_time() that takes a HERE MAP API 							  key and generate a dictionnary of bicycle diatance, travel-time and base-time betweens these two locations.

- final_programme function: Takes 2 GPS Locations and return the route between those locations periodically with a period of 20min.

- Execuition field : executes the final_programme with a given locations

- Tests classes : Test possible bugs which can occure in during the programme using the unittests framework. 



