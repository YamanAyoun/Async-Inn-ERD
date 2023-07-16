# Async-Inn
## Name: Yaman Ayoun.
## Date: 16-7-2023.

## Async Inn ERD
![ERD](Asserts/lab11.png)

### I have the following tables:
* Room: Every Item in this table is a room, it has an Room_ID which is a primary key, a nickname to descripe it, a layout and a Amenities.
* Location: the location has an Location_ID, name, address, city, state, and phone number in a CK.
* Amenities: It has PK Amenities_ID Every Item in this table is an amenitie which has a name.
* AmenitiesRoom: It has two FK; because this table is responsible of connecting both of Room and Amenities tables.
* HotelRoom: its contains two FK. it connect every room with a hotel, and has a property called price and name and pet frindly and CK RoomNumber.
