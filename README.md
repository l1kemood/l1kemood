# Coach appointment system

## Introduction
This system is a web-based coach reservation system, which provides members with the function of booking fitness courses with coaches. Members can register as members of the system, choose a fitness program that suits them, and book a fitness class with the right instructor. The system provides functions for different user types, including managers, members and coaches.

## Technology stack
- Back-end: Spring Boot, MyBatis Plus
- Front-end: jQuery, AJAX
- Database: MySQL

## System functions
### 1. The manager
- Maintain the system master file
- Send marketing notices to members who are about to expire
- View all appointments
- Access statistical reports related to business
- Raise/lower the rank of the trainer

### 2. Customers
- Register as a new member
- Log in to your account and make an appointment
- View reservation history
- View the status of the current appointment
- Modify personal data

### 3. Coach
- Login Account
- View your appointment history
- View the status of the current appointment

## Coach rankings
Coaches are ranked from three to five stars based on experience, and members match coaches at different levels depending on the program they purchase.

## Reservation process
1. Member Registration: New users need to register as members in the system first.
2. Purchase Plan: Members must purchase a fitness plan valid for 6 or 12 months before booking:
- Silver Program: Three-star coach
- Gold Program: Four-star coach
- Diamond Project: Five Star Coach
3. Booking a Coach: After purchasing the plan, members can select the appropriate coach, date and time to make an appointment.

## Management process

1. User query: Administrators can view user information.
2. User management: The administrator can modify the user star rating, modify the number of members, modify the password, change the user role, delete the user.
3. Information management: Administrators may edit and delete notices.
4. order management: Administrators can view and delete orders.

## Use examples
Visit the home page of this system:
[coach] reservation system home page (http://120.26.207.137:5500/Mainpage.html)

## Legal Statement
The agreements included in this system are designed to provide appropriate legal protection for the user and the fitness center. When using this system, please abide by the corresponding agreement content.

<!---
l1kemood/l1kemood is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
