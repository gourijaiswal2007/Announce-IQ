# Manual Test Plan

Record actual observations on the version tested. Do not mark Pass/Fail until you run each case.

| ID | Action/input | Expected result | Actual result | Status |
|---|---|---|---|---|
| T1 | Log in with valid Student demo credentials | Student setup/dashboard flow opens |Student dashboard opened after login | Pass |
| T2 | Attempt login with invalid credentials | Access is rejected | Student Dashboard Rejected After Invalid Login | Pass |
| T3 | Search for a distinctive word in a sample announcement | Matching results or a clear no-results state appears | Announcements were displayed after Searching| Pass |
| T4 | Apply a category/department filter and change sort order | List reflects the selected filter/order | Announcements were on the list according to the sorting and category filter | Pass |
| T5 | Save an announcement and open Saved announcements | Item appears during the active page session | Saved Announcements were Available on the Saved Section | Pass |
| T6 | Publish a sample announcement as a publisher role | Item appears in current demo session; it is not delivered to other users | It was appeared in the relevant Demo| Pass |
| T7 | Open an item requiring registration without a URL | UI explains/alerts that no registration URL is available | It was asking for the Name | Pass |

# Feedback log
## User Feedback
- **Prototype reviewed:** Announce IQ
- **Feedback method:** Informal peer review and prototype usability testing
- **Participants:** 3 peer reviewers
- **Date:** 23/10/26

### Feedback 1: Interest-Based Announcements and Category Visibility
- **Original comment:** "I like the Interest based questions so that we get notified about things only we like."
- **Issue or suggestion:** Announcement categories should be easily identified, and the interest questionnaire could include more diverse options.
- **Proposed improvement:** Improve category visibility and filtering, and consider adding more varied interests, clubs, activities, and learning opportunities to the questionnaire.
- **Status:** Proposed, not yet implemented.

### Feedback 2: Saved Announcement Persistence
- **Original comment:** "Saved announcements should remain available after refreshing the page."
- **Issue or suggestion:** Saved announcements should remain accessible after the page is refreshed.
- **Proposed improvement:** Review and improve the saving mechanism so saved announcements can persist after a page refresh or when the user returns to the website.
- **Status:** Proposed, not yet implemented.

### Feedback 3: Clearer Announcement Publishing Scope
- **Original comment:** "Users should know whether a published announcement reaches other students."
- **Issue or suggestion:** Users may assume that publishing an announcement automatically shares it with other students.
- **Proposed improvement:** Add a prominent notice explaining that Announce IQ is a demonstration prototype and that publishing an announcement does not automatically deliver it to other students.
- **Status:** Proposed, not yet implemented.

