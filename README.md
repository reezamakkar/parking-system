# parking-system


Low level design for Vehicle parking system. The vehicle parking system has one entry gate and finite space for parking all kinds of vehicles, like cars, bikes and trucks.  


## Assumptions

1. The parking lot should have multiple floors where customers can park their cars.

2. Customers can collect a parking ticket from the entry point and can pay the parking fee at the exit points on their way out.

3. The system should not allow more vehicles than the maximum capacity of the parking lot. If the parking is full, the system should be able to show a message at the entrance panel and on the parking display board on the ground floor.

4. Each parking floor will have many parking spots. The system should support multiple types of parking spots such as Compact, Large, Handicapped, Motorcycle, etc.

5. The system should support parking for different types of vehicles like car, truck, van, motorcycle, etc.

6. Each parking floor should have a display board showing any free parking spot for each spot type.

7. The system should support a per-hour parking fee model. For example, customers have to pay $4 for the first hour, $3.5 for the second and third hours, and $2.5 for all the remaining hours.
