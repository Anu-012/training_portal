## ServiceNow Project: Training Management in ServiceNow

## Traditional System
- Current system relies on email communication between HRs/coordinators and employees to provide training details within their competency.
- Trainings outside their competencies are difficult to attend given the waiting period
- Leads to delays and potential risk of losing training opportunities.
- Sudden emails on short notice also can lead to lack of preparedness for essential trainings.
  
## Features
- Select desirable trainings With personalized training plans based on individual needs and career goals.
- Data security ensured through RBACs(Role Based) and Data Access Controls (table and field level. data policies).
- Provides a user-friendly interface to explore and enroll in training sessions.

## Repo Structure
1. /architecture: Design overview
2. /screenshots: Training Portal UI/Backend screenshot
3. /technologies used: Record Producers, Business Rules, Catalog Client Scripts, Notifications, Survey Designer
4. /flows: approval workflows created

## How it Works
1. User logs into the training portal- appending the native instance URL with /learning.
2. User submits the request via the portal.
3. Record Producers creates a record in the respective tables.
4. Flow Designer triggers the approval workflow based on the form submitted.
5. Notifications sent to the competency head or the manager.
6. Training scheduled and tracked accordingly.


