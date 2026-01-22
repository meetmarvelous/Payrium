# Payrium – Phase 1 (Web Wallet + DAO)

Phase 1 focuses on **UX validation**, **user feedback**, and **investor/demo readiness**. No advanced DeFi, no treasury control, no native apps.

## 2. Product Goals (Phase 1)

- Support **BNB Smart Chain (primary)**
- Enable **basic wallet actions** (create, import, send, receive, view balances)
- Enable **UI-level token swap**
- Implement **DAO voting (read + vote only)**
- Maintain **mobile-first UX**

## 3. Existing Assets (Input)

Already completed:

- Fully designed **HTML pages** for:
  - Onboarding
  - Wallet creation/import
  - Dashboard & portfolio
  - Send / Receive
  - Swap UI
  - Settings & security
  - DAO governance screens

**Supported Assets:**

- Native BNB
- ERC-20, BSC tokens
- PUM token (BNB chain)

---

## 5. Functional Requirements

### 5.1 Onboarding

- Welcome screens
- Create wallet
- Import wallet (seed phrase)
- Secure confirmation

---

### 5.2 Wallet Core

- Generate EVM wallet
- Display address
- Show balances
- Copy / QR receive

---

### 5.3 Send / Receive

- Send native BNB
- Send ERC-20 tokens
- Gas estimation
- Transaction status

---

### 5.4 Portfolio Dashboard

- Token list
- Total balance
- Activity history

---

### 5.5 Swap (Basic)

- Token A → Token B
- Quote preview
- Submit transaction

---

### 5.6 Settings & Security

- Export seed phrase
- Change PIN
- App info

---

## 6. DAO Specification (MVP)

### 6.1 Access Rules

- Wallet must hold **PUM > 0** to access DAO
- Non-holders see preview + CTA

---

### 6.2 Voting Power

- 1 PUM = 1 vote
- No cap per wallet

---

### 6.3 Snapshot Logic

- Voting power snapshotted at proposal start
- Read PUM balance at block height

---

### 6.4 Proposal Control

- Proposal creation restricted to **admin wallet only**
- Admin wallet address configurable

---

### 6.5 Proposal Lifecycle

- Duration: 3 days
- Auto-close after expiry

---

### 6.6 Execution

- Result display only
- No smart contract execution

---

### 6.7 DAO Scope

- Product features
- Roadmap priorities
- Community decisions

No financial actions.

## 10. Validation Output

Phase 1 success =

- Users can create/import wallets
- Send & receive tokens
- View balances
- Vote in DAO
- Provide UX feedback
