# Movie Theater Ticket Kiosk

This project is a guided software engineering tools practice exercise based on a Movie Theater Self-Service Ticket Kiosk. The system allows customers to view available movies and showtimes, choose an available seat, purchase a ticket, and receive a confirmation. The system must also prevent the same seat from being sold twice.

## System Requirements

1. A customer can view available movies and showtimes.
2. A customer can choose an available seat.
3. A customer can purchase a ticket.
4. The system provides a confirmation.
5. The system must prevent the same seat from being sold twice.

## Project Scope

This homework focuses on practicing GitHub repository management, requirements tracking, project boards, and UML modeling using the movie theater ticket kiosk example.

# Expanded Use Case — Purchase Ticket

**Primary Actor:** Customer

**Precondition:** The customer has selected an available movie/showtime and an available seat.

**Main Steps:**
1. Customer selects a movie showtime.
2. The kiosk displays the available seats.
3. Customer selects an available seat.
4. The kiosk requests the ticket purchase.
5. The system verifies that the selected seat is still available.
6. The system processes the payment.
7. The kiosk confirms the purchase and provides the ticket confirmation.

**Postcondition:** The ticket purchase is confirmed and the selected seat is no longer available for another purchase.

# Phase 6 — Purchase Ticket Sequence Diagram

Participants:
- Customer
- Kiosk Interface
- Ticket Service
- Payment Service
- Seat Database

Interaction order:
1. Customer selects showtime.
2. Kiosk requests available seats.
3. Ticket Service checks the Seat Database for available seats.
4. Seat Database returns available seats.
5. Customer selects a seat.
6. Ticket Service checks seat availability.
7. Payment Service processes payment.
8. Payment Service confirms the purchase.
9. Ticket Service sends the confirmation to the Kiosk Interface.
10. Kiosk Interface displays the confirmation to the Customer.

Time flows from top to bottom.


