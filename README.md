# Vleafy--Hotel-Booking-Website-
This is a complete hotel booking website that uses Google Sheets as a database to manage room information, availability, pricing, and bookings. The system features dynamic pricing, real-time availability checking, and a responsive design that works on all devices.
Key Features
1. Frontend Website
Beautiful, responsive design that works on desktop and mobile

Room browsing with images and descriptions

Date selection with check-in/check-out calendar

Real-time price calculation based on:

Room type selection

Number of guests (adults/children)

Breakfast options

Seasonal pricing

Booking form with validation

Room comparison feature

2. Google Sheets Database
The system uses Google Sheets as the backend with these sheets:

RoomTypes: Room details, base prices, and capacity

Availability: Date-based room availability tracking

Bookings: Customer reservation records

RatePlans: Pricing options (with/without breakfast)

Services: Additional services like airport transfers

3. Dynamic Pricing Engine
Calculates prices in real-time based on:

Base room rate

Number of guests (extra person/child charges)

Selected rate plans (with/without breakfast)

Length of stay

Displays detailed price breakdown to users

4. Google Sheets API Integration
Reads room data and availability from Sheets

Writes new bookings back to Sheets

Uses REST API with proper authentication

How It Works
User visits website and searches for availability

Website queries Google Sheets via API for room data and availability

Dynamic pricing calculated based on user selections

User completes booking form and submits

Booking data sent to Google Sheets for storage

Confirmation shown to user

Technical Architecture
text
User Browser (HTML/CSS/JS) ↔ Google Sheets API ↔ Google Sheets (Database)
Benefits of This Approach
No complex backend needed - Google Sheets acts as the database

Easy to manage - Update room details directly in Sheets

Cost-effective - No database hosting costs

Familiar interface - Manage data in spreadsheet format

Real-time updates - Changes in Sheets immediately reflect on website

Setup Requirements
Google Sheets document with proper structure

Google Cloud API key with Sheets API enabled

Web hosting for the HTML/CSS/JS files

(Optional) Custom domain name

This system provides hotels with a complete booking solution without the complexity of traditional database management, making it perfect for small to medium-sized hotels and resorts.

