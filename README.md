# Coding Test: Poya Day Dhamma Sermon Booking Web Application

### Requirements
- Should be used Laravel and Vue3

### Description:
Shraddha Media Network wants a web application to allow users to book the Poya Day Dhamma Sermon online. The application will have 12 Poya days in a year, and there will be only one Dhamma Sermon available for booking on each Poya day. The following requirements should be met:

### Public Page
- Create a public page that displays the current status of bookings for the Dhamma Sermon.
- The page should show all 12 Poya days of the year.
- For each Poya day, display the booking status (e.g., available, requested, booked).
- Only available dates can be requested for booking.

### User Registration and Login
- Implement user registration and login functionality.
- During user registration, capture the following information: First Name, Last Name, Email, WhatsApp Number, and Address.
- Validate the registration form fields appropriately.
- After successful registration, users should be able to log in to the application.

### Booking Request
- Allow registered users to request a booking for a specific Poya day.
- If a user is not logged in, prompt them to log in or sign up before making a booking request.
- Once logged in, users can select an available Poya day and request a booking.
- After submitting the booking request, the Poya day should display the status as "Requested" on the public page.

### Backend Administration
- Create a backend administration interface to manage booking requests.
- Authorized administrators should be able to view and process booking requests.
- Display the list of requested Poya days and their corresponding booking details.
- Allow administrators to approve or reject each booking request.
- If a booking request is rejected, the Poya day should be marked as available again on the public page.
- If a booking request is approved, the Poya day should be marked as "Booked" on the public page, and the user should be notified.

### Bank Payment Slip Upload
- Provide an option for users to upload a bank payment slip after their booking request is approved.
- Add an option for users to upload the payment slip from their account.
- Store the uploaded payment slip securely on the server.
- Display the uploaded payment slip to the administrators for verification purposes.


# Suggested Tests

### Backend Tests:
- User Registration: Test the user registration functionality, including validation of input fields.
- User Login: Test the user login functionality, including authentication and error handling.
- Booking Request: Test the process of submitting a booking request and updating the status on the public page.
- Backend Administration: Test the backend administration interface, including viewing, approving, and rejecting booking requests.
- Bank Payment Slip Upload: Test the functionality of uploading and storing bank payment slips securely.

### Frontend Tests:
- User Login Form: Test the user login form, including input validation and error messages.
- User Registration Form: Test the user registration form, including field validation and error handling.
- Booking Request Process: Test the booking request process from the frontend, including selecting available dates and submitting requests.
- Backend Administration Interface: Test the functionality of the administration interface, including viewing and processing booking requests.
- Bank Payment Slip Upload: Test the frontend functionality of uploading bank payment slips and displaying them in the user's account.

## Recommended Time Frame
- Reading and Understanding the Requirements: 15-30 minutes
- Planning Phase: 30-60 minutes
- Project Setup and Environment Configuration: 15-30 minutes
- Backend Implementation: 1-3 hours
- Frontend Implementation: 1-3 hours
- Testing and Documentation: 1-2 hours


# Project Submission:
#### Send us the github link of your project with all instruction to run the application.
