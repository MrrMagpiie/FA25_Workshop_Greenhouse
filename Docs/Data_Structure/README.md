# Data Structure

## The Location
the basic structure centers around the "Location" of everything. 
a location is a class that everything is attached to and then gets called to display for front end.

## Tank
A tank is a subtype of location that has sensors and hardware dedicated to tanks attached to it as well as an attribute stating whether it is a maintank for water and nutrient mixing or a subtank for nutrients.

## Hardware
Hardware is a class for storing hardware state and location information.

## Hardware Type
Hardware type is a class that gives information about a specific type of hardware. each Hardware object will have Hardware type.

## Sensor
Sensor is a class for storing sensor reading and location information.

## Sensor Type
Sensor type is a class that gives information about a specific type of sensor. each Sensor object will have a Sensor Type.

## Plant
A plant is a class that stores and displays information tanken from the location relevant to that plant
if we end up creating a database with best environmental data for specific plants we will also need a plant type class.
