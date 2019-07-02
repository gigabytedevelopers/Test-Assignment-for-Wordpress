# Test-Assignment-for-Wordpress
https://app.codeline.io/#/projects/3025/tasks/26733 - User Authentication Secured!

We need to create a simple Wordpress plugin which will be integrated into the Hotel Booking System in the previous task. 
This plugin should be able to connect to Laravel API and allow to list available rooms from the Hotel and book rooms by customers.

## Plugin Interface

### 1.1 Room List
#### Fields:
- Start Date
- End Date
- Total Nights (calculate from start and end dates)
- Image
- Room Name
- Room Type
- Total Price

#### Functionality:
- Allow users to select a room (after selecting the system should redirect the user to Reservation Page)

### 1.2 Reservation Page
- The system should display booking details (room information, booking date information, total price). 
- Customer details form:
- Customer Fullname (required)
- Customer Phone (required)
- Confirmation button to book the selected room.
- Protect form submission with Google ReCaptcha
