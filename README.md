# BookMe-App-FE
Source code for the **BookMe** booking application embedded in an `iframe`. This application provides a full booking flow for service-based businesses, allowing customers to select services, choose time slots, enter details, and make payments directly within the widget on a business's website.

## Overview

The **BookMe** booking application is designed to be integrated as an `iframe` on various websites. It offers a seamless user experience for booking services and handling payments without redirecting customers away from the business's site.

### Key Features

- **Service Selection**: Allows customers to select from a list of services offered by the business.
- **Real-Time Availability**: Shows available time slots for each service or staff member.
- **Integrated Payment Processing**: Securely handle payments directly within the booking flow using Stripe, PayPal, or other popular payment gateways.
- **Responsive Design**: Fully responsive layout optimized for desktop, tablet, and mobile devices.

## Tech Stack

- **Frontend Framework**: React
- **Backend**:  Java Spring
- **Database**: MongoDB or PostgreSQL for storing booking and user data
- **Payment Integration**: Stripe, PayPal APIs
- **Deployment**: Hosted on AWS.

## Getting Started

To run the booking application locally for development purposes, follow these steps:

### Prerequisites

- Node.js (v14.x or later) and npm/yarn installed
- A running instance of the backend API (set up separately)
- An account with Stripe, PayPal, or another payment gateway for integration testing

## License

This project is licensed under the MIT License.
