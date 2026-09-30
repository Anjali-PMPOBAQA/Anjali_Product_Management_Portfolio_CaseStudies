# UX Flow & Figma Handoff

## 1. UX Objective

Translate the configurable subscription package requirements into a simple end-to-end experience connecting the Business Admin's Backoffice configuration with the customer's subscription journey.

The UX focuses on keeping configuration flexible for business users while keeping the customer experience simple and easy to understand.

---

# 2. End-to-End UX Flow

```text
BUSINESS ADMIN
      ↓
Package Management
      ↓
Create / Edit Package
      ↓
Configure Package Details
      ↓
Configure Pricing & Duration
      ↓
Configure Benefits
      ↓
Configure Expiry & Priority
      ↓
Review / Preview
      ↓
Activate Package
      ↓
       ↓
CUSTOMER EXPERIENCE
       ↓
Subscription Packages
       ↓
View Package Details
       ↓
Compare Available Packages
       ↓
Select Package
       ↓
Payment
       ↓
Subscription Activated
       ↓
Benefits / Entitlement
       ↓
Expiry / Renewal
```

---

# 3. Backoffice UX

### Screen 1 — Package Management

Business Admin can:

* View existing packages
* Create a new package
* Edit a package
* Activate/deactivate a package
* View package status
* View package priority

---

### Screen 2 — Create / Edit Package

The Business Admin configures:

* Package name
* Package type
* Duration
* Price
* Promotional price
* Status

---

### Screen 3 — Configure Benefits

The Business Admin can:

* View available benefits
* Add benefits to a package
* Remove benefits
* Create differentiated package offerings

---

### Screen 4 — Expiry & Priority

The Business Admin configures:

* Package expiry
* Display priority
* Activation status

The priority determines the order in which eligible packages appear on the customer-facing experience.

---

### Screen 5 — Review / Activate

Before activation, the Business Admin should be able to review the configured package information.

The package can then be activated according to the applicable business rules.

---

# 4. Customer UX

### Screen 6 — Subscription Package Listing

Customers can see:

* Available package names
* Duration
* Price
* Promotional price, where applicable
* Key benefits
* Promotional information
* Subscribe CTA

Packages are displayed according to the configured priority.

---

### Screen 7 — Package Details

The customer can review the selected package and understand:

* What is included
* Duration
* Price
* Promotional offer
* Relevant expiry information

---

### Screen 8 — Package Selection & Subscription

The customer selects the package and proceeds through the subscription/payment journey.

---

### Screen 9 — Subscription Activated

After successful payment, the subscription becomes active and the customer receives the applicable package entitlements.

---

# 5. UX Principle

> **Complexity belongs in configuration; simplicity belongs in the customer experience.**

The Backoffice provides the flexibility required by the business.

The customer-facing experience presents only the information needed to understand and select a subscription.

---

# 6. Figma Prototype

The Figma prototype will demonstrate the key product flows rather than the complete online library experience.

### Prototype Scope

**Backoffice**

Package Management → Create/Edit → Pricing & Duration → Benefits → Expiry & Priority → Review → Activate

**Customer**

Package Listing → Package Details → Select Package → Payment → Subscription Activated

---

## Figma Link

**Prototype:** [Add Figma link]

---

## Product Traceability

| Product Requirement     | UX Representation           |
| ----------------------- | --------------------------- |
| Package creation        | Create/Edit Package         |
| Pricing                 | Pricing configuration       |
| Duration                | Package configuration       |
| Benefits                | Benefits configuration      |
| Expiry                  | Expiry configuration        |
| Priority                | Priority configuration      |
| Activation              | Review / Activate           |
| Frontend display        | Package Listing             |
| Customer selection      | Package Details / Selection |
| Subscription activation | Activation confirmation     |

This creates traceability from **Product Requirements → UX Flow → Figma Prototype**.
