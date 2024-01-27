Title: Smart Waste Collection System

Group Member:

- SAIFUL IMRAN BIN SAIFUL BAHRI				B032110273
- TEOH JIA QI								          B032110286
- WAN MAHIRAH BINTI WAN MASHRUHIM			B032110244
- SALAH MOHAMMED SALEH AYASH			    B032110467

OBJECTIVE
- To develop an application that makes waste collection more efficient.
- To enable the users to give feedback about the status of a smart bin through the app and notify an 
  urgent clean-up.
- To ensure that the workers have an easier time during their job by notifying the status and location 
  of the smart bins through the application using geolocation.

PROJECT SCOPE
Module Development
1. Micro:bit Sensing Module
   This system will integrate with a device called a smart bin which contains several sensors such 
   as a fill-level sensor and temperature sensor. These sensors work by noticing users via 
   notifications through the apps so that the user knows the state of the smart bin while ensuring 
   the safety of the neighbourhood in terms of health. The sensors also work in a real-time system 
   so that the user is always updated to current situations.
   *Fill-level sensor
   *Temperature monitoring
   *Weight monitoring 

2. Administration Module
   This module enables the admin to do some administration jobs.  The admin will assign a driver to 
   every pick up either fixed or demand pickup.  Admin may also add a new driver or change the driver 
   status from active to inactive or vice versa.  The schedule will only be assigned to the active users.
   *Assign drivers
   *Manage drivers

3. Tracking Module
   This module is responsible for displaying the map, the location of the smart bins and the location 
   of the garbage trucks. It will also keep track of the status of the smart bins. For example, the 
   “green” status of a smart bin means that it is in good condition and “red” means the smart bin is 
   either damaged or contains inappropriate waste.
   *Geographic Information System (GIS) implementation

4. Reporting Module
   This module enables more interaction among users and the system.  It will get real-time updates 
   for the users about the bin.  The users may make a demand to collect their waste.   Any important 
   notifications or alerts will also be sent to the users. 
   * Real-time updates
   * Notification and alerts

Target User
1. Users that have bought a smart bin.
   *Notify a smart bin that is full to be picked up or broken.
   *Look up the location of the smart bins that are nearby.
   *Access the map of their current location from the app.

2. Workers that are responsible for the clean up of the smart bins.
   *Look up the location of the smart bins.
   *Access the map of their current location from the app.
   *See the navigation path recommended by the admin.
   *Notify the admin if necessary.

3. Admin
   *See the location of trucks that will pick up waste from the smart bins.
   *Assign drivers according to their schedules and demand from users.
   *Recommend a navigation path if necessary.

DATABASE
We use Firebase as the database to store our data. The database consists of 5 tables which are:
Admin - Admin_Id, Username, Password
User - User_Id, Username, User_FullName, User_IC, User_PhoneNumber, Password
Driver - Driver_Id, Username, Driver_FullName, Driver_IC, Driver_PhoneNumber, Password, Email, Location, Active
Bin - Bin_Id, Bin_Alias, Bin_Location, Bin_Temperature, Bin_Weight, Bin_fillLevel, User_Id
Schedule - Schedule_Id, Date, Status, Type, Bin_Id, Driver_Id

HARDWARE & SOFTWARE
Hardware: mobile devices, laptop/desktop, microbit
Software: Android Studio, Github, Firebase

CONCLUSION
In conclusion, the Smart Waste Collection System is introduced to address the limitations of 
traditional waste practices amid urbanisation. This chapter outlines the system's key features, 
including IoT sensors, real-time data analysis, and an efficient waste collection app. By tackling 
issues with current waste collection services, the project aims to enhance user feedback, improve 
worker operations through geolocation, and bring overall efficiency to waste collection. The 
upcoming chapters will provide technical details on how this system can revolutionise waste 
practices for cleaner and more sustainable urban environments.
