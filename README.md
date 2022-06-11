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
## Planning Each Feature
analyze complexity of each feature and plan tasks that are related to be accomplished
1. Add/Remove/Edit vehicle: To add, remove or modify a vehicle.

2. Search Vehcile: To search for vehicles by type and availability.

3. Update car log: To add or update a car log entry, such as refueling, cleaning, damage, etc.

4. Return a vehicle: To return a vehicle which was checked-out to a member.

5. Search catalog: To search for vehicles by type and availability.

6. Send notifications: Alert to remind when car must be returned.

7. Search vehicle: To search through car log.

8. Register new account/Cancel membership: To add a new member or cancel an existing membership.

9. Database: Inventory of all automobiles along recording a log and updating changes.

10. Reserve vehicle: To reserve a vehicle. Ending with optional rental insurance to balance. 

11. Add equipment: To add an equipment to a reservation like navigation, child seat, etc.

12. Add services: To add services to a reservation such as roadside assistance, additional driver, wifi, etc.
## Designing Each Feature
defining the feature priorities. which includes technical design and framework
1. Add/Remove/Edit vehicle:
    - Vehicle Inventory
        - ID, type, description, date

2. Search Vehicle:
    - Vehicle
        - ID, stock number, seat capacity, barcode, add-ons, status, model, make, year, mileage

3. Update car log:
    - Vehicle Reservation
        - date, status, due date, return date, pickup location, return location, fetch details

4. Return a vehicle:
    - Vehicle
        - return vehicle

5. Search catalog:
    - Member
        - get reservations

6. Send notifications:
    - Notification
        - id, date, content, send

## Building Each Feature
feature prototype is created. The unit is tested, inspected and then approved. finally, completed feature moved to the main build