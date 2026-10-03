# Movie Theater Ticket Kiosk

This project models a simple self-service ticket kiosk for a movie theater. Customers can view available movies and showtimes, select an open seat, and purchase a ticket, receiving a confirmation once the purchase is complete. The system is designed to ensure that no seat can be sold to more than one customer.


**Movie Kiosk Use Case**

Actor: Customer
System boundary: Movie Theater Ticket Kiosk
Use cases: View Showtimes, Select Seat, Purchase Ticket

The Customer is the only actor, and the Customer uses all three use cases.

**Purchase Ticket**

Primary Actor: Customer

Precondition: The kiosk is on and working, and the Customer has picked a showtime that still has open seats.

Main Steps:

The Customer picks a movie and showtime.
The kiosk shows the seat map.
The Customer picks their seat(s).
The kiosk shows the order summary and total price.
The Customer confirms the order.
The Customer pays at the payment terminal.
The kiosk approves the payment and reserves the seat(s).
The kiosk prints the ticket(s) and shows a confirmation message.

Postcondition: The Customer has a ticket, the seat(s) are marked as sold, and the payment is saved.
