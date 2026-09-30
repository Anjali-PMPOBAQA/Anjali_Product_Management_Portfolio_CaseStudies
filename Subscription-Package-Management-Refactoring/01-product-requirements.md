# Product Requirements — Subscription & Package Management Refactoring

## 1. Product Context

The existing online book library used a fixed subscription package model with predefined package types such as Basic, Premium and Ultra.

The product was refactored to introduce a configurable package management model, allowing business teams to create and manage different subscription offerings through Backoffice.

---

## 2. Problem Statement

The fixed package model limited the business team's ability to introduce new package variations based on changing business and promotional needs.

For example, seasonal or promotional offerings such as Diwali, Christmas or Summer Vacation packages could require different combinations of duration, pricing, benefits and expiry.

Creating such variations through a fixed package structure increased dependency on product and engineering changes.

### Core Problem

How might we enable business teams to create, modify and manage different subscription offerings through a configurable package framework?

---

## 3. Product Objective

Create a configurable subscription package framework that enables business teams to manage:

* Package type
* Duration
* Price
* Promotional price
* Benefits
* Expiry
* Display priority
* Active/inactive status

The configuration should flow consistently from Backoffice to the customer-facing experience.

---

## 4. Target Users

### Business Admin

Needs to create, configure, prioritize and manage subscription packages without requiring a new fixed package structure for every offering.

### Customer

Needs to understand package pricing, duration and benefits clearly before selecting a subscription.

---

## 5. Product Requirements

### PR-01 — Package Creation

The system should allow Business Admins to create a subscription package with configurable attributes.

Required attributes include:

* Package name
* Package type
* Duration
* Price
* Promotional price, where applicable
* Benefits
* Expiry
* Priority
* Status

### PR-02 — Package Editing

Business Admins should be able to modify configurable package attributes according to applicable business rules.

### PR-03 — Package Activation

Business Admins should be able to activate or deactivate packages.

Only eligible active packages should be available for customer selection.

### PR-04 — Benefit Configuration

Business Admins should be able to configure package-specific benefits.

This allows different packages to provide different customer propositions.

### PR-05 — Expiry Configuration

Business Admins should be able to configure package duration and/or expiry according to the defined business rules.

Expired packages should not be offered to new customers where the applicable rules prohibit new subscriptions.

### PR-06 — Package Priority

Business Admins should be able to configure the display priority of active packages.

The frontend should display active packages according to the configured priority.

### PR-07 — Pricing

The system should support:

* Standard package price
* Promotional package price, where applicable

The applicable price should be clearly displayed to customers.

### PR-08 — Frontend Display

The customer-facing experience should display relevant package information, including:

* Package name
* Duration
* Price
* Promotional price, where applicable
* Benefits
* Relevant promotional or expiry information
* Subscribe action

---

## 6. Key Business Rules

1. A package must contain all mandatory information before activation.
2. Only active and eligible packages should be displayed to customers.
3. Package priority determines the display order of active packages.
4. Expired packages should follow defined availability rules.
5. Promotional pricing should only apply when configured and valid.
6. Package benefits should be mapped to the selected package.
7. Backoffice configuration should be reflected consistently in the customer-facing experience.

---

## 7. MVP Scope

### Included

* Package creation
* Package editing
* Package activation/deactivation
* Package type configuration
* Duration configuration
* Pricing configuration
* Promotional pricing
* Benefit configuration
* Expiry configuration
* Priority configuration
* Frontend package display

### Out of Scope for MVP

* Customer segmentation
* Personalization
* Package experimentation
* Advanced package analytics
* Automated recommendations

---

## 8. Product Principle

**Complexity belongs in configuration; simplicity belongs in the customer experience.**

The Backoffice should provide the flexibility required by business teams while the customer-facing experience should remain simple and easy to understand.

---

## 9. Expected Product Outcome

The configurable model should provide a reusable foundation for regular, seasonal and promotional subscription offerings without requiring a new fixed package structure for each variation.

It should also reduce routine dependency on engineering for package configuration while maintaining consistency between Backoffice configuration and the customer experience.

