## Parking Lot system
### Feature Description
There should a Parking with multi-levels which allows you to park any type of vehicle. Also, It tracks entry and exit of veicle and release the parking lot on the exit, provide availability of praking for a vehicle type.

### Low level design details
- ParkingLot class - It should be a static class which ensures that only one instance exist for this ParkingLot system. It contains below methods
    - Park
    - UnPark
    - Display Availability
- Level class will provide parking levels information
    - Spot availability
    - Park Vehile at spot
    - UnPark Vehicle from the spot
- ParkingSpot class - A parking spot provides spot information with following methods
    - Park Vehicle
    - UnPark Vehicle
    - GetSpotNumber
    - Get Parked Vehicle
    - Spot availability
- Vehicle class holds vehicle information like Vehicle Type and Number
- VehicleType Enum provide different vehicle types
- Main class will provide the usage of this parking lot system.