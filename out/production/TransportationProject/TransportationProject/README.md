# PROJECT NAME : UG CAMPUS ROUTE FINDER

## INTRODUCTION

The UG Campus Route Finder is a Java application designed to assist users in finding the best route from 
one location to another within the University of Ghana (UG) campus. The application utilizes the Dijkstra
algorithm to determine the shortest distance and best arrival time between two locations on campus.
Users can select their desired starting location (Location A) and destination (Location B) within the campus 
and obtain multiple route options, along with significant landmarks along each route. 

This README file provides an overview of the project and its functionalities.

## FEATURES

Calculates the best route from Location A to Location B based on the shortest distance and best arrival time 
considering traffic conditions.
Utilizes various algorithms, including Dijkstra's algorithm, to determine the shortest path and distance.
Sorts the routes based on distance and arrival time, allowing the user to choose from the most suitable options.
Implements a searching algorithm that generates routes from a selected landmark to the destination, providing 
multiple route options.
Provides significant landmarks along each route to assist users in navigating through the campus.

## REQUIREMENTS

To run the UG Campus Route Finder application, the following requirements must be met:

* Java Development Kit (JDK) 8 or higher must be installed on the system.
* Internet connectivity to access map data and calculate real-time distances.

## INSTALLATION
1. Clone the project repository from GitHub using the following command:
        git clone git clone https://github.com/DCIT204-GROUP2/shortest-distance-finder-java.git 
2. Open the project in your preferred Java development environment (e.g., IntelliJ, Eclipse, etc.).
3. Build the project to resolve dependencies and compile the source code.
4. Ensure that the system has an active internet connection to retrieve map data and calculate 
distances and traffic conditions.


## USAGE
* Launch the UG Campus Route Finder application.
* Enter the starting location (Location A) and destination (Location B) within the UG campus.
* Select the desired algorithm (e.g., Dijkstra's algorithm) to calculate the best route efficiency.
* The application will display multiple route options with their corresponding distances, arrival times, and 
  significant landmarks.
* If the user wants to search for routes from a landmark to the destination, enter the landmark name (e.g., "Bank").
* The system will provide all routes associated with the landmark and the destination, along with significant 
  landmarks for each route.
* Choose the preferred route based on the displayed information.
* Follow the provided route and landmarks to navigate through the UG campus efficiently.


## IMPLEMENTATION DETAILS

The UG Campus Route Finder application is implemented using Java and incorporates various algorithms and
techniques taught in class to ensure efficiency. One of the algorithms used is Dijkstra's algorithm, which 
calculates the shortest path and distance between nodes in the graph. The provided code snippet showcases the 
implementation of the Dijkstra class, which includes the core logic for finding the shortest path and distance 
using Dijkstra's algorithm.


## GROUP 2 MEMBERS' INFORMATION

1. Emmanuel Yartey (10987736) -             S-yartey007
2. Lartey Solomon (10980887)  -             GeekYbruCe
3. Ivy Owusu(10985154)        -             IvyOwusu
4. Lamptey Joseph Odarkwei(10953249)-       
5. Marie-Pearl Akoto(10947903)-             mariepearl
6. Elisha Teye(10940920)-                   
7. Audrey Amarh(10947541)-                  asheleyaudrey
8. Osei- Bonsu Karlyn(10970624)-            
