# DISHA---Women-Safety-Application
DISHA is a Women Safety Application designed to provide assistance and information in emergency situations. The application includes features such as user authentication, emergency contact management, and integration with a city map to access emergency services efficiently.

#Features

User Authentication: Users can sign up for a new account or log in with an existing account. Account details are stored securely.
Emergency Contact Management: Users are required to set up an emergency contact list during account creation. The list ensures quick access to important contacts in case of emergencies.
Admin Authentication: Admins can sign up for a new account or log in with an existing account. Admin accounts have additional privileges, including access to the city map details.
City Map Integration: The application includes a city map feature that allows users to find the nearest police station, request emergency assistance, and discover the fastest path from one location to another.
Shortest Path Algorithm: The application uses the Floyd-Warshall algorithm to find the shortest paths between all pairs of locations in the city map.

#Compiling and Running
g++ main.cpp -o DISHA
./DISHA

#Usage

Sign up for a new user or admin account.
Log in with your credentials.
Explore the application features, including emergency contact management and city map services.
License

This project is licensed under the MIT License.

#Acknowledgments

The city map and shortest path algorithms are implemented using C++.
The application uses file-based storage for user and admin data.
The project structure and code organization follow best OOPs practices for C++ applications.
