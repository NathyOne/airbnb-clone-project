# airbnb-clone-project
The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb.
It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. 
It uses Technologies like Python, MySQL, GraphQL, Redis, and Django. 


#Team Roles
1-Backend developer: implement the core of an app—its algorithms and business logic.
2-Database Administrator: Focuses on database optimization, indexing, Normalization, etc.

#Technology Stack
1-Django
2-Rest Api
3-Graphql
4-MySql
5-Redis

#Database Design
Users
1- The user can have multiple properties.
2- The user can make multiple Bookings.
3- The user can give one review for one property.


Properties
1- Properties can only have one owner.
2- Properties can be booked only by one user.

Bookings
1- Identifies the user who made the booking.
2- Identifies the date it's booked.

Reviews
1- Identifies a user who made the review.
2- Identifies the property reviewed.

Payments
1- Identifies the user who made the payment.
2- Identifies the properties on which payment was made.

#Feature Breakdown
User management: Manages a user by assigning a unique identity to a user and a relationship with other entities.
Property management: Manages each property and the association with the user and other entities
Booking system: Manages bookings and registers each with the associated user and property.

#API Security
Authentication: Validating user exist or not in the database.
Authorization: Who is allowed to access specific content.
Rate limiting: For how long does a single request stay alive before the server responds with "too long time taken" or something similar.

#Why 
Why protecting user data is importanet?
Protecting user data: protecting user data is crucial in avoiding any attacks and securing confidential information of the user from anyone who is unauthorized.
securing payment?
securing payment: securing payments is directly related to financial risks who should be avoided at all cost.










