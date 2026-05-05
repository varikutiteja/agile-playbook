# User Story Templates & Examples

A practical guide to writing clear, actionable user stories that
engineering teams can actually build from.

## The golden formula
As a [type of user]
I want to [do something]
So that [I get some benefit]

---

## Acceptance criteria format — Given / When / Then
Given [some context]
When [I do something]
Then [this should happen]

---

## Real examples from FinTech & SaaS

### Example 1 — Onboarding
**User story:**
As a new user
I want to complete account setup in under 5 minutes
So that I can start using the platform without frustration

**Acceptance criteria:**
Given I am a new user who just signed up
When I follow the onboarding flow
Then I should complete setup in 5 steps or fewer
And I should see a progress indicator at each step
And I should receive a confirmation email within 2 minutes

---

### Example 2 — Dashboard
**User story:**
As a trading operations manager
I want to see all open positions in one dashboard
So that I can make faster decisions without switching tools

**Acceptance criteria:**
Given I am logged in as an operations manager
When I open the dashboard
Then I should see all open positions updated in real time
And I should be able to filter by asset class and status
And the page should load in under 3 seconds

---

### Example 3 — Compliance
**User story:**
As a compliance officer
I want to export audit logs in CSV format
So that I can submit reports to regulators on time

**Acceptance criteria:**
Given I am logged in as a compliance officer
When I click Export Audit Log
Then a CSV file should download within 10 seconds
And the file should include date, user, action, and IP address
And logs should be filterable by date range before export

---

## Story sizing guide

| Size | Story points | Description |
|---|---|---|
| XS | 1 | Trivial change, under 2 hours |
| S | 2 | Small, clear, half a day |
| M | 3 | Medium complexity, 1 day |
| L | 5 | Large, needs discussion, 2-3 days |
| XL | 8 | Very large, consider splitting |
| XXL | 13 | Too big, must split before sprint |

---

## Signs of a bad user story

- No acceptance criteria
- Written from system perspective not user perspective
- Too vague — "improve performance"
- Too large — more than 8 story points
- Missing the WHY — no "so that" clause