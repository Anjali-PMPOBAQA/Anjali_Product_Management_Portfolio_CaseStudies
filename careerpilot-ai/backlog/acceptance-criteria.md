# CareerPilot AI — Acceptance Criteria

This document defines the acceptance criteria for the core CareerPilot AI MVP user stories.

---

# Epic 1 — Career Assessment & Profile

## US-01 — Enter Professional Experience

**Business Intent:**  
Capture the user's professional background as the foundation for career-fit analysis.

### Acceptance Criteria

- User can enter their professional experience.
- User can provide relevant role and experience details.
- Required fields must be completed before continuing.
- Entered information is saved to the user's profile.
- User can review the information before proceeding.
- Saved information is available to subsequent assessment steps.

---

## US-02 — Capture Current Role and Experience

**Business Intent:**  
Understand the user's current career context.

### Acceptance Criteria

- User can enter or select their current role.
- User can provide their industry.
- User can specify years of professional experience.
- User can edit the information before completing the assessment.
- Information is saved successfully.
- The information is used as an input to Career Fit Analysis.

---

## US-03 — Edit Professional Profile

**Business Intent:**  
Allow users to maintain an accurate professional profile.

### Acceptance Criteria

- User can view previously entered profile information.
- User can edit profile fields.
- User can save updated information.
- Updated information replaces the previous value.
- Updated profile information is used in future analysis.

---

## US-04 — Add Skills and Experience

**Business Intent:**  
Capture the user's relevant capabilities.

### Acceptance Criteria

- User can search and select predefined skills.
- User can categorize skills as Technical, Functional, Domain or Transferable.
- User can add a custom skill when the required skill is not available.
- User can select multiple skills.
- User can remove an incorrectly selected skill.
- User can save the completed skill list.
- Saved skills are available to Career Fit Analysis.

### Edge Cases

- Duplicate skills should not be added.
- Empty skill entries should not be saved.
- User should be able to correct an incorrectly categorized skill.

---

## US-05 — Define Skill Proficiency

**Business Intent:**  
Capture the user's level of capability for each selected skill.

### Acceptance Criteria

- User can assign a proficiency level to each skill.
- Available levels include Beginner, Intermediate and Advanced.
- User can update a proficiency level.
- Selected proficiency is saved with the corresponding skill.
- Proficiency information is passed to Career Fit Analysis.

---

## US-06 — Identify Transferable Skills

**Business Intent:**  
Help users understand capabilities that may apply to other career paths.

### Acceptance Criteria

- System analyzes the user's skills and professional experience.
- System identifies potential transferable skills.
- Transferable skills are displayed clearly.
- User can review the identified skills.
- User can indicate whether a suggested transferable skill is relevant.
- Confirmed transferable skills are included in Career Fit Analysis.
- User can update the information if a suggestion is inaccurate.

---

## US-07 — Define Career Goals and Priorities

**Business Intent:**  
Understand what the user wants from their next career direction.

### Acceptance Criteria

- User can select a primary career goal.
- User can select multiple priorities.
- Available priorities include growth, flexibility, stability, learning, leadership and work-life balance.
- User can indicate relative importance of priorities.
- User can add a custom goal when required.
- User can review and modify selections.
- Saved priorities are used in career recommendations and comparison.

---

## US-08 — Define Preferred Work Style

**Business Intent:**  
Ensure recommendations align with the user's preferred way of working.

### Acceptance Criteria

- User can indicate preference for individual, collaborative or combined work.
- User can indicate preference for structured or flexible environments.
- User can indicate preferred work characteristics such as people-facing, analytical, creative, technical or business-oriented work.
- User can select multiple preferences where applicable.
- User can add a custom preference.
- User can review and modify preferences.
- Saved preferences are used in career recommendations.

---

## US-09 — Define Financial and Career Constraints

**Business Intent:**  
Ensure recommendations consider practical career constraints.

### Acceptance Criteria

- User can select preferred work arrangement such as Remote, Hybrid or On-site.
- User can provide geographic or location preferences.
- User can indicate career risk preference.
- User can provide a minimum income expectation.
- User can specify working-hour preferences.
- User can indicate relocation flexibility.
- User can indicate preference for career stability.
- User can add a custom constraint.
- User can review and modify constraints.
- Saved constraints are considered during recommendation generation.

---

# Epic 2 — Career Fit & Options

## US-10 — Generate Career Fit Analysis

**Business Intent:**  
Evaluate potential career directions using the user's complete profile.

### Acceptance Criteria

- System uses professional experience, skills and proficiency.
- System considers transferable skills.
- System considers career goals and priorities.
- System considers work-style preferences.
- System considers financial and practical constraints.
- System generates a career-fit analysis.
- Analysis provides understandable reasoning for the identified fit.

---

## US-11 — View Best-Fit Career Options

**Business Intent:**  
Provide a focused set of relevant career directions.

### Acceptance Criteria

- System generates a focused set of best-fit career options.
- The MVP displays up to 3 primary career options.
- Each option includes a clear career title.
- Each option includes a short explanation of why it may fit.
- User can open and explore each option.
- Recommendations are based on the user's assessment information.

---

## US-12 — View Alternative Career Options

**Business Intent:**  
Give users additional possibilities without overwhelming them.

### Acceptance Criteria

- System provides additional probable career options.
- The MVP can display up to 5 alternative options.
- Alternative options are clearly separated from primary recommendations.
- User can explore each alternative.
- Alternatives are generated using the user's profile and preferences.

---

## US-13 — Understand Recommendation Rationale

**Business Intent:**  
Improve transparency and user trust.

### Acceptance Criteria

- Each recommendation provides an understandable rationale.
- Rationale references relevant user inputs.
- User can identify key factors contributing to the recommendation.
- Recommendation rationale should not present uncertain outcomes as guaranteed results.
- User can review their profile if a recommendation appears inaccurate.

---

# Epic 3 — Compare & Decide

## US-14 — Compare Career Options

**Business Intent:**  
Help users evaluate multiple career directions side by side.

### Acceptance Criteria

- User can select career options for comparison.
- User can compare options using relevant criteria.
- Comparison includes factors such as skills fit, growth, flexibility, stability and constraints.
- User can view differences between options clearly.
- User can return to the available career options.

---

## US-15 — Review Career Trade-offs

**Business Intent:**  
Help users understand strengths and limitations before deciding.

### Acceptance Criteria

- User can review key strengths for each option.
- User can review potential challenges or trade-offs.
- User can review fit factors.
- Information is presented consistently across options.
- User can use the information to support their decision.

---

## US-16 — Select Preferred Career Direction

**Business Intent:**  
Move the user from exploration toward a clear direction.

### Acceptance Criteria

- User can select a preferred career direction.
- User can review the selected option before confirming.
- User can change the selection before confirmation.
- Confirmed direction is saved.
- The selected direction becomes the basis for the transition plan.

---

# Epic 4 — Transition Plan & Refinement

## US-17 — Create Initial Transition Plan

**Business Intent:**  
Convert the selected career direction into actionable next steps.

### Acceptance Criteria

- System generates an initial transition plan based on the selected career direction.
- Plan includes recommended next steps.
- Plan identifies relevant skill or knowledge gaps where applicable.
- Plan can include learning, experience-building or preparation activities.
- User can review the plan.
- User can identify the immediate next action.

---

## US-18 — Refine Career Recommendation

**Business Intent:**  
Allow the product to improve recommendations based on user feedback.

### Acceptance Criteria

- User can provide feedback on recommendations.
- User can modify relevant preferences or constraints.
- Updated information can trigger recommendation refinement.
- Refined recommendations reflect the updated inputs.
- User can review the updated recommendation.
- The refinement loop supports continuous personalization.

---

# MVP Acceptance Summary

The MVP should allow a user to:

1. Create a professional profile.
2. Define skills and experience.
3. Identify transferable capabilities.
4. Define goals, work preferences and constraints.
5. Receive career-fit analysis.
6. Explore primary and alternative career options.
7. Understand recommendation rationale.
8. Compare career options.
9. Select a preferred direction.
10. Receive an initial transition plan.

The overall MVP journey is:

**Assessment → Recommendation → Comparison → Decision → Plan**

---

# Acceptance Criteria Principles

Acceptance criteria should be:

- Clear
- Testable
- User-focused
- Traceable to a product requirement
- Specific enough for development and QA validation
- Flexible enough to avoid prescribing unnecessary implementation details
