# Personal Expense Tracker Application

## Question 1: Agile Principles

### Agile Manifesto Values

1. **Individuals and Interactions over Processes and Tools**  
The team should focus on communication between developers, testers, and the Product Owner. This helps make sure that the app is easy for users to understand and use.

2. **Working Software over Comprehensive Documentation**  
The team should prioritize building working features like expense logging and monthly summaries instead of spending too much time on large documents.

3. **Customer Collaboration over Contract Negotiation**  
The Product Owner can give feedback after each sprint. For example, they may request simpler reports or new budget alerts.

4. **Responding to Change over Following a Plan**  
Requirements may change once users see the app. Agile allows the backlog to be updated throughout development.

### Agile vs. Waterfall

#### Benefits of Agile
- Frequent feedback from the Product Owner.
- Early delivery of working software.
- Easier adaptation to changing requirements.

#### Challenges of Agile
- Product Owner may not always be available.
- Scope creep from too many feature requests.
- Team coordination can become difficult.

#### Mitigation Strategies
- Schedule regular meetings with the Product Owner.
- Keep sprint scope fixed during the sprint.
- Use Scrum Boards and daily stand-ups for communication.

---

## Question 2: Agile Practices (Scrum & XP)

### Scrum Initiation

- Sprint Length: 2 weeks
- Release Length: 4 sprints
- Velocity: 18 story points
- Estimation Method: Planning Poker using Fibonacci points

### Example User Stories

| User Story | Points |
|---|---:|
| Log Expense | 5 |
| Categorize Transactions | 3 |
| View Monthly Summary | 5 |
| Set Budget Goal | 5 |
| Generate Spending Report | 8 |

Example Story:

**As an individual user, I want to log expenses with an amount and category, so that I can track my spending habits.**

### Sprint Planning

| Sprint | Stories | Total Points |
|---|---|---:|
| Sprint 1 | Log Expense, Categorize Transactions, Edit Expense | 11 |
| Sprint 2 | Monthly Summary, Budget Goal, Budget Tracking | 15 |

### Sprint Execution

#### Tasks for “Log Expense”
1. Design expense entry form.
2. Build API endpoint for expenses.
3. Create database table.
4. Write automated validation tests.

The Scrum Board tracks tasks through To Do, In Progress, Testing, and Done columns.

### Sprint Closure

At the end of each sprint:
- The team demonstrates working software during the Sprint Review.
- The team discusses improvements during the Retrospective.

### Scrum Roles

#### Product Owner
- Prioritizes features.
- Represents end users.
- Approves completed work.

#### Scrum Master
- Facilitates Scrum meetings.
- Removes blockers.
- Protects the team from scope creep.

### Scrum vs XP

| Scrum | XP |
|---|---|
| Focuses on project management. | Focuses on engineering practices. |
| Uses roles. | Uses Test-Driven Development and pair programming. |
| Organizes sprint workflow. | Improves code quality and testing. |

Scrum helps organize the project, while XP improves software quality through practices like continuous integration and automated testing.