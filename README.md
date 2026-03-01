#nexapay
NexaPay is a single‑file, front‑end e‑wallet demo UI built with HTML + CSS + vanilla JavaScript. It simulates common wallet actions (top up, send, pay, loans)

---

 Features

- Wallet dashboard
  - Available balance display
  - Auto‑generated 12‑character account number (grouped in 4s)
  - Copy account number to clipboard
- Quick actions
  - Top Up (bank transfer or card)
  - Send money (requires PIN)
  - Pay merchant (requires PIN)
  - Quick Loan (apply + repay, requires PIN)
- Transactions
  - Recent transactions list (last 5)
  - Full transaction history modal
  - Transaction types: `topup`, `sent`, `payment`, `loan`, `repayment`
- Loans
  - Eligibility info (credit score, max eligible amount, APR)
  - Term selection: 3 / 6 / 12 months
  - Simple interest calculation and monthly payment preview
  - Active loan progress + monthly repayment action
- Cards
  - Add card via Top Up flow (stored as last4/name/expiry)
  - Remove saved cards
- Profile
  - Edit name/email/phone
  - Reset wallet (clears all local data)
- Settings
  - Change 4‑digit PIN
- Notifications
  - Seeded welcome/promo/security notifications on first run
  - Badge count for unread notifications
  - Mark single/all as read, clear all
 

Limitations / Disclaimer

-This is a front‑end simulation only:
-No backend
-No real payments, bank transfers, or card processing
-Do not use for real financial data.
