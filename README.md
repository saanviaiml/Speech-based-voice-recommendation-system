# Speech-based-voice-recommendation-system 

The Traffic Management System is a comprehensive software solution designed to handle traffic-related data efficiently. This program supports recording and managing information about vehicles, traffic challans, and traffic control booths. With a user-friendly interface and modular code design, the system is ideal for automating traffic data management processes.

Features
Welcome Screen:
Displays the current date and time and provides navigation to various functionalities through a menu-based interface.

Vehicle Management:

Add new vehicle records (registration number and owner's name).
Search for vehicle details using registration numbers or owner's names.
Challan Management:

Add new challan records.
Search challans by vehicle registration number or owner's name.
Traffic Control Booth Information:

Provides information about traffic control booths in specific locations.
Search Functionality:

Enables users to search for vehicles and challans efficiently.
Help Section:
Offers assistance for using the system.

Technical Details
Programming Language: C++
File Handling: Uses file streams to store and retrieve data for vehicles and challans.
Sleep Functions: Introduces delays for smoother transitions using this_thread::sleep_for and this_thread::sleep_until.
Menu Navigation: Implements nested menus for user interaction.
Prerequisites
A C++ compiler supporting C++11 or later.
System capable of running terminal-based programs.
Pre-created file paths for storing data:
RecordOfTheVehicles.txt
RecordOfTheChallan.txt
How to Run
Compile: Use a C++ compiler to compile the program, e.g.,
bash
Copy code
g++ -o TrafficManagementSystem TrafficManagementSystem.cpp -pthread
Run: Execute the compiled program:
bash
Copy code
./TrafficManagementSystem
Follow the on-screen instructions to interact with the system.
