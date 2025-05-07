# Banking App - Phạm Lê Ngọc Sơn

## Overview
A modern banking application developed by Phạm Lê Ngọc Sơn, featuring a secure digital platform that enables users to manage financial accounts and transactions conveniently via smartphones or web browsers. The application provides essential banking functionalities including account balance viewing, fund transfers, bill payments, check deposits, and card management.

## Project Structure

### Core Directories
- **app/** - Next.js application routes and pages
  - **(auth)/** - Authentication related pages
  - **(root)/** - Main application pages
  - **api/** - Backend API endpoints
  
- **components/** - Reusable UI components
  - **ui/** - Basic UI elements
  - Various feature components (BankCard, TransactionsTable, PaymentTransferForm, etc.)
  
- **types/** - TypeScript type definitions
- **lib/** - Utility functions and shared logic
- **constants/** - Application constants and configuration
- **public/** - Static assets

### Key Technologies
- **Frontend**: Next.js, React, TypeScript, Tailwind CSS
- **UI Components**: Radix UI
- **Form Handling**: React Hook Form with Zod validation
- **Data Visualization**: Chart.js
- **Banking Integration**: Plaid, Dwolla
- **Monitoring**: Sentry

## Features
- **Secure Authentication** - User login and registration with security measures
- **Account Dashboard** - Overview of all linked accounts and total balance
- **Transaction History** - Detailed view of recent transactions with filters
- **Fund Transfers** - Transfer money between accounts or to other users
- **Bill Payments** - Pay bills directly through the application
- **Bank Account Linking** - Connect multiple bank accounts via Plaid integration
- **Analytics** - Visual representations of spending patterns
- **Card Management** - Control debit/credit cards, view details, and transactions

## Getting Started

### Prerequisites
- Node.js (v18 or later)
- npm or yarn

### Installation
1. Clone the repository
   ```
   git clone https://github.com/phamlengocson/banking-app.git
   cd banking-app
   ```

2. Install dependencies
   ```
   npm install
   # or
   yarn install
   ```

3. Run the development server
   ```
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application

### Building for Production
```
npm run build
npm start
# or
yarn build
yarn start
```

## Usage Guide
1. **Register/Login** - Create an account or login with existing credentials
2. **Link Bank Accounts** - Connect your external bank accounts using Plaid
3. **View Dashboard** - See all your accounts and total balance at a glance
4. **Make Transfers** - Use the payment/transfer form to move money
5. **Track Transactions** - View and filter your transaction history
6. **Manage Cards** - Control your debit/credit cards

## Contact
For questions or feedback, please contact Phạm Lê Ngọc Sơn 
email: son.phamlengoc@gmail.com
sdt: 0334229371
---
© 2024 Phạm Lê Ngọc Sơn. All Rights Reserved.
