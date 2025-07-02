# The Wild Oasis

This is a modern, responsive web application for managing a hotel business. Authorized users can login and see current bookings, check guests in and out, update cabins, create new authorized users, and update their own name, password, and avatar image. This project was built as part of the Udemy course "The Ultimate React Course 2025: React, Next.js, Redux & More" by Jonas Schmedtmann.

### To do:

There is currently no functionality in the app for adding new bookings. There is also no functionality for updating bookings (number of guests, number of nights, etc.). Both of these could conceivably be done with the same interface, perhaps a modal like the add/update cabins.

Authorized users can delete bookings, but it might be better to archive bookings so that they are no longer visible in the application but remain in the database. Currently deleting a booking deletes it from the database.

There are undoubtedly many more possible enhancements, but this is just a show project.

## Demo

Try the live app: [The Wild Oasis](https://mikkelsons-wild-oasis.netlify.app/login/)
(contact me for login information, mikkelson_shawn@yahoo.com)

## Tech Stack

**React**: Frontend library for building the user interface.
**Supabase**: Database for storing user data, bookings, cabins, and settings.
**React Query**: Manages remote state.
**React Router**: Handles client-side routing for navigation.
**Compound Components**: Easily customizable and flexible components.
**Styled Components**: CSS framework for styling.
**Context API**: Manage global state, including Dark Mode for the entire application

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mikkelsons/the-wild-oasis.git
   cd the-wild-oasis
   ```

2. Install dependencies:

   ```bash
    npm install
   ```

   or

   ```bash
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   or
   ```bash
   yarn dev
   ```
   The app should now be running at http://localhost:5173

## Usage

- **Login Page** You will need a login and password to gain access to the app. Contact me at mikkelson_shawn@yahoo.com to request one.
- **Dashboard**: Displays statistics for recent bookings and sales, with a filter option. A reactive pie chart and line graph to easily view and compare stay durations, sales, and extras sales.
- **Bookings Page**: View and manage bookings, statuses, payment received, guest details.
- **Cabins Page**: View and manage available cabins, prices, photos, capacities, discounts.
- **Users page**: Add new authorized users.
- **Setings**: Update settings for bookings, e.g., min/max nights per booking, breakfast price.
- **Update Account**: Update user name, user avatar image, and user password for the current user.
- **Dark Mode**: Easily toggle between light and dark mode. Default is the browser's default.
