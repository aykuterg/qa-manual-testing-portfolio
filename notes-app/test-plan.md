\# Test Plan — Notes Management



\## Objective



Verify that a logged-in user can create, view, edit, complete, delete, and search notes according to the defined acceptance criteria.



\## Scope



\### In Scope



\- Create note

\- Notes list

\- Edit note

\- Edit persistence after refresh

\- Completed status

\- Completed-state persistence after refresh

\- Delete note

\- Search by title

\- Search by description

\- Hiding non-matching notes

\- Basic data-integrity checks



\### Out of Scope



\- Performance testing

\- Security testing

\- API testing

\- Database validation

\- Cross-browser testing

\- Mobile testing



\## Test Approach



Testing was performed manually using:



\- Acceptance-criteria-based testing

\- Positive testing

\- Persistence testing

\- Data-integrity testing

\- Targeted negative testing



\## Key Risks



\- Edited note data may not persist after refresh.

\- Completed state may not persist after refresh.

\- Editing one note may incorrectly affect another note.

\- Deleting one note may incorrectly delete or affect another note.

\- Search may fail to return valid matches from the title or description.



\## Requirement Limitation



Search is required to match the title or description.



Case sensitivity and partial-match rules were not defined, so those behaviors were not used as PASS/FAIL criteria.

