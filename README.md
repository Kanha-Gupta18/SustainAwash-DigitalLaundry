# Sustainawash

Sustainawash is a lightweight, web-based laundry management system designed to streamline the check-in and collection process for campus hostels or dormitories. It replaces paper receipts with digital QR codes, making the laundry process sustainable and efficient.

## Features

1. Student Check-In Portal

Digital Entry: Students input their name, laundry card number, and phone number.

Itemized Tracking: detailed counters for specific clothing items (Jeans, Shirts, Towels, etc.).

Smart Limits: Automatically enforces a maximum limit of 10 items per batch to ensure fair usage.

Instant Receipt: Generates a unique QR Code containing the batch ID upon submission.

2. Staff Check-Out Portal

Built-in Scanner: Uses the device's camera to scan student QR codes instantly.

Order Verification: Displays the student's details and the exact list of clothes submitted.

Status Tracking: Staff can mark orders as "Collected," preventing duplicate pickups.

3. Data Persistence

No Server Required: Uses the browser's LocalStorage to save laundry batches, making it perfect for demos and hackathons without needing a backend database.

## Tech Stack

Frontend: HTML5, CSS3 (Responsive Design)

Logic: Vanilla JavaScript

Libraries:

qrcode.js (for generating QR codes)

html5-qrcode (for scanning QR codes)

Database: Browser LocalStorage

## How to Use

For Students (Drop-off)

Open the application and ensure you are on the "Student Check-In" tab.

Enter your details (Name, Card No, Phone).

Select the number of clothes you are submitting (Max 10).

Click "Generate Receipt".

Take a screenshot of the generated QR Code.

For Staff (Collection)

Switch to the "Staff Check-Out" tab.

Grant camera permissions if prompted.

Scan the student's QR code.

Review the laundry items on the screen.

Click "Mark as Collected" to complete the process.

## Setup & Installation

Since this is a static web application, no complex installation is required.

Download the code:
Clone this repository or download the Sustainawash.html file.

Run the App:
Simply double-click Sustainawash.html to open it in any modern web browser (Chrome, Edge, Firefox, Safari).

Note: For the QR Scanner to work on mobile devices, the file typically needs to be hosted (e.g., GitHub Pages) because cameras require a secure context (HTTPS) or localhost.

## Mobile Compatibility

The application is fully responsive and adapts to mobile screens, making it easy for students to use on their phones and for staff to use tablets for scanning.

Built for a cleaner, greener campus.
