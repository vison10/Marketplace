<div align="center">

# 🛍️ MERN Marketplace 2.0

### A full-stack marketplace with shopping, payments, and real-time auctions

**Built by Ansh Sharma**

<br/>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)

</div>

---

## ✨ About the Project

MERN Marketplace 2.0 is an online marketplace built with **MongoDB, Express.js, React, and Node.js**. It brings product discovery, shopping, order management, payment processing, and live auctions into one application.

## 🚀 Features

- 👤 **Seller accounts** — support for marketplace sellers
- 🔎 **Product discovery** — product search and suggestions
- 🛒 **Shopping cart** — manage selected products
- 📦 **Order management** — manage marketplace orders
- 💳 **Payments** — Stripe payment integration
- ⚡ **Live auctions** — real-time bidding powered by Socket.IO

## 🧰 Tech Stack

| Technology | Role |
|---|---|
| React | Frontend user interface |
| Node.js | JavaScript runtime for the backend |
| Express.js | Backend application and APIs |
| MongoDB | Database |
| Socket.IO | Real-time auction communication |
| Stripe | Payment processing |

## 🖼️ Preview

<div align="center">
  <img src="https://s3.amazonaws.com/mernbook/git+/marketplace.png" alt="Marketplace preview" width="80%" />
  <br/><br/>
  <img src="https://mernbook.s3.amazonaws.com/git+/marketplace-bidding.png" alt="Live auction and bidding preview" width="80%" />
</div>

## ⚙️ Getting Started

### Prerequisites

- Node.js
- npm or Yarn
- MongoDB
- Stripe test account and test credentials

### Installation

1. Start MongoDB.
2. Install the project dependencies from the project root:

   ```bash
   npm install
   ```

3. Configure the Stripe test API keys and Stripe Connect Client ID in `config/config.js`.
4. Start the development application:

   ```bash
   npm run development
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🔐 Configuration & Security

- Use Stripe test credentials during development.
- Keep secret keys, database credentials, and other private values out of source control.
- Do not commit `.env` files or credentials to a public repository.
- Confirm the configuration values required by your local copy before running the application.

---

<div align="center">

**Made with ❤️ by Ansh Sharma**

</div>
