# CarRental
A Car Rental System is a software built to handle the renting of automobiles for a short period of time, generally ranging from a few hours to a few weeks. 

# Project Description
## What this application does:
what problem does this solve?
A car rental system often has numerous local branches (to allow its user to return a vehicle to a different location), and is primarily located near airports or busy city areas. 

People frequency travel and compared to buying a brand new car, car rentals are very appealing. Being without a car for 'x' amount of days while traveling can significantly effect the experience. 

Therefore, having an application that is centered around management, collaboration and mitigating risks for users is crucial. This application focuses on easing the entire managment process for a variety of departments. Ensuring the user interface is fast, easy, and is organized. 
## Technologies you used:
what software tools was used and why these?
## Challenges faced & Future features
what aspects were challenging? what can be implemented in the future.

# How to Install and Run
step-by-step description of how to get the development environment set and running.

# Testing Application
write tests for your application. Then provide code examples and how to run them. Explain testing methods and reasoning.

# System Requirements
1. The system will support the renting of different automobiles like cars, trucks, SUVs, vans, and motorcycles.

2. Each vehicle should be added with a unique barcode and other details, including a parking stall number which helps to locate the vehicle.

3. The system should be able to retrieve information like which member took a particular vehicle or what vehicles have been rented out by a specific member.

4. The system should collect a late-fee for vehicles returned after the due date.

5. Members should be able to search the vehicle inventory and reserve any available vehicle.

6. The system should be able to send notifications whenever the reservation is approaching the pick-up date, as well as when the vehicle is nearing the due date or has not been returned within the due date.

7. The system will be able to read barcodes from vehicles.

8. Members should be able to cancel their reservations.

9. The system should maintain a vehicle log to track all events related to the vehicles.

10. Members can add rental insurance to their reservation.

11. Members can rent additional equipment, like navigation, child seat, ski rack, etc.

12. Members can add additional services to their reservation, such as roadside assistance, additional driver, wifi, etc.

# Development Process
## Gathering Data
The target audience for this software is geared towards car rental businesses. The goal of businesses that provide car rentals is to develop franchises. Which expands to catering to a larger range of clients. To succed in the car rental industry you must know the importance of having micro-niche specialists. Likewise, using a micro-niche software to handle the logs of renting automobiles.
## Developing an Overall Model
detailed domain models, which will then be merged into one overall model that acts as a rough outline of the system
There are (4) main 'Users' in this system:
- **Receptionist**: Mainly responsible for adding and modifying vehicles and workers. Receptionists can also reserve vehicles
- **Member**: All members can search the catalog, as well as reserve, pick-up, and return a vehicle
- **System**: Mainly responsible for sending notifications about overdue vehicles, canceled reservation, etc.
- **Worker**: Mainly responsible for taking care of a returned vehicle and updating the vehicle log
## Developing Features List
- Request Reservation
    - Add Equipment
    - Add service
    - Add rental insurance
    - Add additional driver
- Create Reservation
- Remove Reservation
- Update Reservation
- Add Vehicle
    - Add Barcode
- Modify Vehicle
    - Modify Barcode
- Remove Vehicle
    - Remove Barcode
- Pickup Vehicle
- Return Vehicle
- Update Balance
- Update Car Log
- Search Vehicle Inventory
- Create New Account
- Update/ Cancel Account
- Login/ Logout
- Send Overdue Notification
- Send Reservation Notification
- Send Reservation Canceled Notification
## Planning Each Feature
analyze complexity of each feature and plan tasks that are related to be accomplished
1. Reservation
    - This class will be responsible for managing reservations for a vehicle.
2. Vehicle
    - The basic building block of the system. Every vehicle will have a barcode, license plate number, passenger capacity, model, make, mileage, etc. Vehicles can be of multiple types, like car, truck, SUV, etc.
3. Account
    - Mainly, we will have two types of accounts in the system, one will be a general member and the other will be a receptionist. Another account can be of the worker taking care of the returned vehicle.
4. Inventory System
    - The main part of the organization for which this software has been designed.
5. Equipment
    - Stores details about the various types of equipment that members can add to their reservation.
6. Service
    - Stores details about the various types of service that members can add to their reservation, such as additional drivers, roadside assistance, etc.
7. Rental Insurance
    - Stores details about the various rental insurances that members can add to their reservation.
8. Bill
    - Contains different bill-items for every charge for the reservation.
9. Notification
    - Will take care of sending notifications to members.
10. Vehicle Log
    - To keep track of all the events related to a vehicle.
11. Vehicle Locator
    - The car rental system will have multiple locations, each location will have attributes like ‘Name’ to distinguish it from any other locations and ‘Address’ which defines the address of the rental location.
## Designing Each Feature
defining the feature priorities. which includes technical design and framework
1. Reservation
    - 
2. Vehicle
    - 
3. Account
    - 
4. Inventory
    - 
5. Equipment
    - 
6. Service
    - 
7. Rental Insurance
    - 
8. Bill
    - 
9. Notification
    - 
10. Car Log
    - 
11. Car Locator
    - 
## Building Each Feature
feature prototype is created. The unit is tested, inspected and then approved. finally, completed feature moved to the main build