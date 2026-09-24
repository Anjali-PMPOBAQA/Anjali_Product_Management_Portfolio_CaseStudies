# 04 — Prioritization & MVP Decisions

## 1. Prioritization Objective

The purpose of prioritization was to determine which capabilities should be included in the MVP to test the core product hypothesis without making the initial product unnecessarily complex.

The central question was:

> Which capabilities are essential to help an experienced professional move from career uncertainty to a clear and actionable career direction?

---

## 2. Prioritization Framework

A RICE-style framework was used to structure prioritization decisions.

**RICE = Reach × Impact × Confidence ÷ Effort**

The framework considers:

- **Reach** — How many users or journeys could benefit
- **Impact** — How strongly the capability contributes to the product outcome
- **Confidence** — How confident we are in the expected value
- **Effort** — Relative implementation complexity

The framework was used as a decision-support mechanism rather than as a claim of measured market data.

---

## 3. Core Product Outcome

The primary outcome for the MVP is:

**Move the user from career uncertainty to a clear career direction and actionable next step.**

Therefore, features directly supporting this outcome receive priority.

---

## 4. Feature Prioritization

| Capability | User Value | MVP Priority | Decision |
|---|---|---|---|
| User Profile & Assessment | Establishes the information needed for personalization | P0 | Include |
| Career Fit Analysis | Connects user capabilities to potential career directions | P0 | Include |
| Career Options | Gives users relevant directions to explore | P0 | Include |
| Option Comparison | Helps users understand trade-offs | P0 | Include |
| Preferred Career Direction | Converts exploration into a decision | P0 | Include |
| Initial Transition Plan | Converts the decision into action | P0 | Include |
| Feedback & Refinement | Enables improvement of recommendations | P1 | Include / refine |
| Advanced Personalization | Improves depth of personalization | P1 | Later |
| External Integrations | Expands connected experiences | P2 | Defer |
| Community Features | Adds peer/community interaction | P2 | Defer |
| Automated Job Applications | Automates downstream job-search activity | P2 | Defer |
| Deep Financial Modelling | Adds more detailed financial decision support | P2 | Defer |

---

## 5. Why Assessment Comes First

Career recommendations need context.

Without understanding the user's:

- Experience
- Skills
- Skill proficiency
- Goals
- Work preferences
- Constraints

the product cannot provide meaningful personalization.

Therefore:

**Assessment → Career Fit Analysis**

is the foundation of the MVP.

---

## 6. Why Career Fit Analysis Is Core

Career Fit Analysis connects what the user already has with possible future directions.

It considers:

**Experience + Skills + Transferable Capabilities + Goals + Preferences + Constraints**

The purpose is not simply to identify skills, but to determine how those capabilities could relate to different career directions.

---

## 7. Why Career Options Are Limited

The MVP intentionally provides:

### 3 Best-Fit Options

These represent the primary career directions identified as having strong alignment with the user's profile.

### 5 Probable Alternatives

These provide additional possibilities for exploration without creating an unnecessarily large list.

The decision supports the principle:

> Reduce decision complexity rather than increase information overload.

---

## 8. Why Comparison Is a Core MVP Capability

Providing career options alone does not necessarily help a user make a decision.

Users need to understand the differences and trade-offs between options.

Comparison therefore acts as the bridge between:

**Discover**

and

**Decide**

Users can evaluate options against factors such as:

- Career fit
- Growth
- Flexibility
- Personal priorities
- Work preferences
- Practical constraints

---

## 9. Why the Transition Plan Is Included

A recommendation without an action path can leave the user in the same state of uncertainty.

The Initial Transition Plan converts:

**Career Direction → Next Steps**

This supports the product goal of helping users move from understanding their options to taking action.

---

## 10. MVP Boundary

### P0 — Core MVP

```text
Assessment
    ↓
Career Fit Analysis
    ↓
Career Options
    ↓
Comparison
    ↓
Preferred Direction
    ↓
Initial Transition Plan
