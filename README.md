# PARKING LOT Management

# General
Parking lot management provides the facility to manage the parking lot efficiently. The list of actions that can be perfromed while using this service are:

 - Park a vehicle
 - Unpark a vehicle
 - Get the status of parking lot
 - Get all registration numbers of vehicles of a particular color
 - Get all slot numbers of vehicles of a particular color
 - Get the slot number for vehicle with the registration number

Also the instructions can be passed to the application as explained [here]() by either by using a text file or by giving one-by-one instructions related to vehicle parking


# Requirements
    - Java 1.8
    - Maven 3.3.9 (or higher)

# Building
In order to build the code follow these steps:
 - Go to `parking_lot` directory
 - Execute `bin/setup` command

# Strat The App
The interaction with the app can be done in two way:
 
 - **First Way**:
   1. Go to parking_lot director
   2. Run command `bin/parking_lot`
   3. An interactive terminal will start. Type the commands. O/P will be displayed below the commad after **Enter** key is pressed. Can be exited by typing **exit**
    
  - **Second Way**:
    1. Go to `parking_lot` directory
    2. Run command `bin/parking_lot FILE_NAME.txt`. Application will look for the file in **parking_lot** directory. If file is not       
      found, it will take the text file  `file_input.txt` present in the `functional_spec/fixtures` directory. O/P will be displayed on 
      the terminal


