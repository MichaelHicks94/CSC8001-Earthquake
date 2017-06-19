# CSC8001-Earthquake
My first piece of coursework for CSC8001. The goal was to create classes to simulate simple earthquake monitoring.  

Problem Specification: 

Define a Java class Earthquake with appropriate fields, methods and constructor to store
and retrieve information about the magnitude, position (latitude and longitude) and year of
the event.

Define a Java class Observatory with appropriate fields, methods and constructor to store
and retrieve the name of the observatory, the name of the country in which it is located, the
year in which earthquake observations started, the area covered by the observatory (in
square kilometres) and a list of Earthquake events that it has recorded. Include methods to
return:
 The largest magnitude earthquake recorded by the observatory.
 The average earthquake magnitude recorded at the observatory.
 A list of all earthquakes recorded at the observatory with a magnitude greater than
a given number.

Define a Java class Monitoring, which holds information about all observatories. Include
methods to return:
 The observatory with the largest average earthquake magnitude.
 The largest magnitude earthquake ever recorded.
 A list of all earthquakes recorded with magnitude greater than a given number.

Define a class MonitoringIO, with a main method which does the following:
 Presents the user with a menu (printed to the console) of features:
o enter observatory data;
o enter earthquake data;
o provide monitoring statistics on largest average earthquake, largest
earthquake ever and all earthquakes with magnitude greater than a given
number; or
o exit
 Takes user input from the console to choose one of the menu features
 Allows the user to input, via the console, the details of observatories and
earthquakes
 After executing one of the features, returns the user to the menu to choose another
option

All classes should be properly documented with javadoc and include appropriate testing
methods.
