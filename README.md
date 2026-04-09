# Comic-Con-Parking-System

### Entities
- vehicles_owners
- vehicle_categories
- vehicles
- reservation_categories
- parking_spots
- zones
- sessions
- payments

### Thought Process
- vehicles_owners - The entrypoint of the DB. It stores the owner personal details
- vehicle_categories - It stores all the categories of the vehicle types
- vehicles - This is table where details of each vehicle is stored
- reservation_categories - All the reservation types are stored here
- parking_spots - All the details of parking spots are stored here. Assume it to show like book my show seat booking where each seat has a seperated id.
- zones - This stores all the zones inside the venue and at which level each zone is situated at.
- sessions - This is the main table it works as an event and stores the info like 'Car A was parked at spot 3A from 10:00 AM to 12:00 PM'
- payments - This tables stores all the info regarding the payments done and it depends on the session.

### Design Choices 
- The fare is calculated based on the type of vehicle, the fare per hour and the duration the vehicle was parked there.
  
