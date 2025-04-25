# Flight-Reservation-System
A console-based Java application that simulates a single-day flight reservation system at Toronto Pearson International Airport (YYZ). This system allows users to view available flights, reserve and cancel seats, view seat layouts, and manage passenger manifests—all through simple command-line interactions.

# Features
Flight Scheduling: Automatically loads flight schedules from a flights.txt file.<br/>
Seat Management: Tracks economy and first-class seat availability and assignments.<br/>
Passenger Operations: Supports reservation, cancellation, and real-time seat manifest tracking.<br/>
Aircraft Management: Includes multiple aircraft models with seat layout generation and display.<br/>
Custom Exceptions: Gracefully handles errors such as flight not found, seat type errors, and duplicate passengers using custom exception classes.<br/>
Interactive Console UI: A command-line interface to issue commands like LIST, RES, CANCEL, SEATS, PASMAN, and MYRES.

# Files 
FlightReservationSystem.java – Main interactive command-line interface.<br/>
FlightManager.java – Core controller managing flights and aircraft.<br/>
Flight.java – Represents a flight and manages seat assignments.<br/>
Aircraft.java – Represents an aircraft and its seat layout.<br/>
Passenger.java – Stores individual passenger details.<br/>
flights.txt – Input file containing daily flight data.<br/>
README.md – Project description.
