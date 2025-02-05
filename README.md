# Project done by Sifiso Smangaliso Dladla
https://github.com/Usmanga-28

Mzansi-Flix
Project Description
Mzansi-Flix is an experimental streaming platform project with the goal of developing a web application served by ReactJS and powered by the Spring framework. 
The project will set up a REST API to manage users, profiles, videos, support tickets, notifications, subscriptions, and a history of entries.

Key Technologies Used:

Frontend: ReactJS

Backend: Spring Framework (Spring Webflux, Spring Mail, Spring Validation)

Database: MongoDB (or any other preferred database)

Video Encoding: ffmpeg

Features
Video Management
Video Upload: [Admin, Affiliate]

Video Deletion: [Admin Only]

Video Editing: [Admin, Affiliate]

Public Playing of a Video: [Admin]

Video Consultation: [User/subscriber minimum]

User Account Management
User Registration: [Any Role]

User Login: [Any User]

Edit Own User (role excluded): [User]

Edit Any User: [Support, Admin]

Delete Own User: [Any Role]

Delete Any User: [Admin, Support]

User Profiles
Creation of Main Profile at First Login: [Any User]

Add Profile: [Any User]

Add Child Profile: [Any User]

Secure Non-Child Profiles: [Any User]

Edit Own Profile: [Any User]

Delete Own Profile: [Any User]

Edit Another User's Profile: [Admin, Support]

Delete Another User's Profile: [Admin, Support]

Support System
Access Support Panel: [Any User]

Create Ticket: [Any User]

Edit Ticket: [Admin, Support]

Delete Ticket: [Admin, Support]

Edit Own Ticket Message: [Any User]

Close Own Ticket: [Any User]

Close Any Issue: [Admin]

Close Assigned Ticket: [Support]

View Own Tickets: [Any User]

View All Tickets: [Admin]

View Assigned Tickets: [Support]

Notifications
Push Notification: [Admin]

Receive Notifications Based on Preferences: [Any User]

Emails
Registration Email: [Any User]

Account Activation via Email: [Any User]

Subscriptions
Subscribe: [Any User]

Change Subscription: [Any User]

Admin Panel
User Listing: [Admin]

User Modification: [Admin]

Subscription Modification: [Admin]

Video Management: [Admin]

Affiliate Panel
Manage Uploaded Videos: [Affiliate]

History System
Action Historization

Access History: [Support, Admin]

Future Improvements
Templates for Emails

Payment System Integration

Timestamp Integration

Video Loader Customization

Multi-Player Playback Synchronization

Use Multiple Encoders with Actuator

Stack Persistence and Fault Tolerance Testing via Chaos Monkeys

