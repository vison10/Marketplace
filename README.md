# MERN Marketplace 2.0

**Developed by:** Ansh Sharma

An online marketplace application built with the MERN stack, featuring seller accounts, product search, shopping cart, order management, Stripe payments, and real-time auctions using Socket.IO.

## Features

- Seller accounts
- Product search and suggestions
- Shopping cart and order management
- Stripe payment processing
- Real-time auctions and bidding with Socket.IO

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Real-time communication:** Socket.IO
- **Payments:** Stripe

## Prerequisites

- Node.js
- npm or Yarn
- MongoDB
- Stripe test account and credentials

## Setup

1. Start MongoDB.
2. Install dependencies from the project root:

   ```bash
   npm install
   ```

3. Configure the Stripe test API keys and Stripe Connect Client ID in `config/config.js`.
4. Start the development application:

   ```bash
   npm run development
   ```

5. Open [http://localhost:3000](http://localhost:3000).

## Environment Configuration

Configure the values required by your project in `config/config.js`. Keep secret keys and credentials private, and do not commit them to a public repository.
