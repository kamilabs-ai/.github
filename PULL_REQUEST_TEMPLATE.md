## Description

*(Briefly describe the changes in this PR)*

Fixes #<issue_number> / Relates to TICKET-XYZ

## Motivation and Context

*(Explain why these changes are necessary. What problem is being solved? What feature is being added?)*

## How Has This Been Implemented?

*(Provide a brief technical overview if necessary. Highlight key decisions, new libraries, or complex logic.)*
*   Updated the `UserProfile` component to fetch data via `useSWR`.
*   Added new Supabase RLS policy for organization members.
*   Refactored `auth-service.ts` to simplify token handling.

## How Has This Been Tested?

*(Describe the manual testing steps performed. Mention relevant automated tests.)*
*   [x] Manual login/logout flow tested successfully.
*   [ ] Added unit tests for `auth-service`.
*   [x] Verified profile updates correctly in the UI.

## Screenshots (if applicable)

*(Add screenshots or GIFs for UI changes)*

## Technical Debt (if applicable)  
*Does this PR introduce or modify any workarounds or sub-optimal patterns?* 
* [ ] Yes (please complete the sections below) 
* [ ] No  

### Description of Technical Debt 
*(Describe the workaround/pattern and why it was necessary)*  

### Impact Analysis 
*(What parts of the system might be affected? Performance/maintenance implications?)*  

### Refactoring Strategy 
*(How and when should this be addressed properly?)*
