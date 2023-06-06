# Project-Hotel
Reservation system for hotel

# Table of contents
+  [1 Requirements](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1-requirements)
+  [1.1 Use-Case diagram](https://github.com/werkovas/Project-Hotel/blob/main/README.md#11-use-case-diagram)
+ [1.1.1 Actors](https://github.com/werkovas/Project-Hotel/blob/main/README.md#111-actors)
+ [1.1.2 Use-Case Diagram](https://github.com/werkovas/Project-Hotel/blob/main/README.md#112-use-case-diagram) 
   + [1.1.3.1 Client: Room reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1131-client-room-reservation)  
   + [1.1.3.2 Client: Use loyalty points](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1132-client-use-loyalty-points)  
  + [1.1.3.3 Client: Pay](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1133-client-pay)  
  + [1.1.3.4 Client: Check reservation status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1134-client-check-reservation-status)  
  + [1.1.3.5 Client: Cancel reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1135-client-cancel-reservation)  
  + [1.1.3.6 Employee: Check room properties](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1136-employee-check-room-properties)  
  + [1.1.3.7 Employee: Update room status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1137-employee-update-room-status)  
  + [1.1.3.8 Employee: Add loyalty points](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1138-employee-add-loyalty-points)  
  + [1.1.3.9 Employee: Select user account](https://github.com/werkovas/Project-Hotel/blob/main/README.md#1139-employee-select-user-account)  
+ [2 Diagrams](https://github.com/werkovas/Project-Hotel/blob/main/README.md#2-diagrams)
+ [2.1 Activity diagrams](https://github.com/werkovas/Project-Hotel/blob/main/README.md#21-activity-diagrams)
   +  [2.1.1 Client: Room reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#211-client-room-reservation)  
  + [2.1.2 Client: Use loyalty points](https://github.com/werkovas/Project-Hotel/blob/main/README.md#212-client-use-loyalty-points)   
  + [2.1.3 Client: Pay](https://github.com/werkovas/Project-Hotel/blob/main/README.md#213-client-pay)  
  + [2.1.4 Client: Check reservation status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#214-client-check-reservation-status)
  + [2.1.5 Client: Cancel reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#215-client-cancel-reservation)  
  + [2.1.6 Employee: Check room properties](https://github.com/werkovas/Project-Hotel/blob/main/README.md#216-employee-check-room-properties)  
  + [2.1.7 Employee: Update room status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#217-employee-update-room-status)  
  + [2.1.8 Employee: Add loyalty points](https://github.com/werkovas/Project-Hotel/blob/main/README.md#218-employee-add-loyalty-points)  
  + [2.1.9 Employee: Select user account](https://github.com/werkovas/Project-Hotel/blob/main/README.md#219-employee-select-user-account)  
+ [2.2 State diagrams](https://github.com/werkovas/Project-Hotel/blob/main/README.md#22-state-diagrams)
  + [2.2.1 Reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#221-reservation)  
  + [2.2.2 Room](https://github.com/werkovas/Project-Hotel/blob/main/README.md#222-room)
+ [3 Design documentation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#3-design-documentation)  
+ [3.1 Object diagram](https://github.com/werkovas/Project-Hotel/blob/main/README.md#31-object-diagram)  
+ [3.2 Sequence diagrams](https://github.com/werkovas/Project-Hotel/blob/main/README.md#32-sequence-diagrams)  
  + [3.2.1 Room reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#321-room-reservation)
  + [3.2.2 Check reservation status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#322-check-reservation-status)
  + [3.2.3 Cancel reservation](https://github.com/werkovas/Project-Hotel/blob/main/README.md#323-cancel-reservation)
  + [3.2.4 Update room status](https://github.com/werkovas/Project-Hotel/blob/main/README.md#324-update-room-status)

## 1. Requirements
## 1.1 Use-Case diagram  
### 1.1.1. Actors  
| Actor | Description |
| :---:   | :---: |
| Client | Application user renting a room.|
| Employee | Application user managing reservations. Has the ability to change the status of the room, rent a room.|

### 1.1.2 Diagram  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/381574e8-23c2-4e2e-9276-c45a098c3b86)

### 1.1.3.1 Client: Room reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/c809b344-89e1-479b-980b-be5eee0d9f83)

### 1.1.3.2 Client: Use loyalty points  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/95122607-74a3-4bb6-8041-b8839928e01e)

### 1.1.3.3 Client: Pay
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/6e4d2b60-9b23-4b8e-950f-c9ae8324952c)

### 1.1.3.4 Client: Check reservation status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/409d4773-8fea-4494-993e-ab43f5609534)

### 1.1.3.5 Client: Cancel reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/7950e966-6e0a-4be9-b005-a04e0971db04)

### 1.1.3.6 Employee: Check room properties  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/0a2b2f5f-505c-4e52-9ab6-ff4459612753)

### 1.1.3.7 Employee: Update room status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/a69a625a-2ba2-4773-a7a9-93d1fd949651)

### 1.1.3.8 Employee: Add loyalty points  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/1f8fd343-3e50-43c3-a3e9-66922eb7e9b9)

### 1.1.3.9 Employee: Select user account  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/8ddbbbb8-aab9-4e77-a282-1154010ea886)

# 2 Diagrams
## 2.1 Activity diagrams

### 2.1.1 Client: Room reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/5811ee02-196a-4631-9d83-d8f25e95a979)

### 2.1.2 Client: Use loyalty points  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/3ca92b46-4b86-46ec-8355-f847484e49ca)

### 2.1.3 Client: Pay  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/00defc0e-2708-46bd-a69d-f8d18b72c633)


### 2.1.4 Client: Check reservation status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/e5178d9a-bd44-4207-8d40-1137034d1a89)


### 2.1.5 Client: Cancel reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/ebd1348c-c9f8-42af-8521-9ccaccc2400a)


### 2.1.6 Employee: Check room properties  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/825e8f16-144c-41d8-aeea-9baf72a798bd)


### 2.1.7 Employee: Update room status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/1f0a7f82-f1f0-4551-90c8-32d041a1d3ad)

### 2.1.8 Employee: Add loyalty points  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/2cb27931-833a-4c5e-906b-9d6f2787001f)

### 2.1.9 Employee: Select user account  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/667cafe5-9674-4490-862d-4b47cf6d00a2)

# 2.2 State diagrams
### 2.2.1 Reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/e4678e3c-40cc-4196-a0ef-45c1d6880ba7)

States description:  
●	CONFIRMED - it is an initial order state. It means that the customer made an order.  
●	CANCELED - can be entered when the customer cancels the reservation.   
●	REJECTED - can be entered when payment for confirmed order is declined.  
●	FINISHED - can be entered when payment is confirmed.  

### 2.2.2 Room  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/1f250834-2437-4669-9cee-f0931aaada61)

States description:  
●	PREPARED - it is an initial room state. It means that the room is prepared for customer check-in.  
●	IN USE - can be entered when the room is in use by a customer.  
●	WAITING FOR CLEANING - can be entered when the room is messy after the customer left.   
# 2.3 Class diagram  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/e5bf83f7-0525-43e1-b682-d956a95f3fe6)

System recognizes following classes:  
●	User - Contains user’s login information.  
●	Customer - Contains basic customer’s information.  
●	LoyaltyPoints - Represents loyalty points collected by customer.  
●	Order - It contains information about order connected to payment.  
●	PaymentInformation - Class contains information about payment for order managed by PaymentService.  
●	Reservation - It contains information about the room reservation.  
●	ReservationStatus - Status of reservation	, enumerable.  
●	Room - Represents information about room for reservation.  
●	RoomStatus - Status of room, enumerable.  

# 3 Design documentation
### 3.1 Object diagram  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/452edb75-3ebf-48a9-be80-c64419cb239d)

The System has instances of classes:  
+ room1  
  + roomNumber - number of reserved room  
  + price - unitary cost of room per day  
  + description - contains basic information about the room.  
  + capacity - number of persons that can rent the room.  
  + status - the state of the room  
+ order1  
  + totalPrice - total price for the order  
  + numberOfPersons - number of persons that will rent the room.  
+ reservation1  
  + checkIn - reservation check-in date  
  + checkOut - reservation check-out date  
  + reservationStatus - the state of the reservation  
+ points_cus1  
  + amount - total amount of customer’s loyalty points  
  + grantDate - date of converting points into the discount  
  + paymentInformation1  
  + type - type of payment method  
  + date - date of payment  
  + amount - total price paid for the order by customer.  
+ user1  
  + login - a unique sequence of characters used to identify a user and allow access to the application.  
  + password - a string of characters that allows access to the application.  
+ customer1  
  + name - name of customer  
  + surname - surname of customer  

# 3.2 Sequence diagram  
### 3.2.1 Room reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/bdd04a34-ed9d-4527-af6c-0ba27f34f3fe)

Identified objects:  
•	ReservationSystem  
•	PaymentProcessing  

Identified actors:  
•	Client  

Diagram description:  
Client begins interaction with reservation system by entering check-in and check-out date, number of persons to let the system check available rooms. Then the system shows matching rooms with their descriptions.  
To begin making reservation Client needs to choose room. Client adds chosen room to order. Then client could use his loyalty points as a discount. After that ReservationSystem decrease the total price of reservation. Client chooses payment method and ReservationSystem shows which payment is chosen by Client to validate.   
Then Client makes payment which is validated by PaymentProcessing system. If payment was accepted ReservationSystem message to Client about success. Then ReservationSystem sends message to Client with payment confirmation.  

### 3.2.2 Check reservation status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/3674ec8f-0c59-4809-82c2-a704ce48d680)

Identified objects:  
● ReservationSystem  

Identified actors:  
● Client  

Diagram description:  
Client sends message to ReservationSystem with request to show reservation status page. ReservationSystem returns requested page. If Client wants to see the previous reservation, he can send a message to show all reservations. If it happens ReservationSystem returns all reservations statuses.  

### 3.2.3 Cancel reservation  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/92dc88d5-5b11-4467-a7cb-853dfd077204)

Identified objects:  
● ReservationSystem  

Identified actors:  
● Client  

Diagram description:  
Client sends a message to ReservationSystem that he wants to see details of active reservation. ReservationSystem return details of reservation and show management options. Client sends a message that he wants to cancel that reservation and ReservationSystem cancels the reservation.  

### 3.2.4 Update room status  
![image](https://github.com/werkovas/Project-Hotel/assets/90156886/3164a2ee-d9f4-4856-b2c2-913e4f731680)

Identified objects:  
● ReservationSystem  

Identified actors:  
● Client  

Diagram description:   
Employee opens the room page. ReservationSystem shows room page with all informations about the room: equipment and relevant details. Employee edits selected room status. The room status can be rented, being cleaned, free.  

