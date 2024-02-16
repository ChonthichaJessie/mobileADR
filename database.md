# Decision record for Permission ADR
---
## Status
Proposed.

## Context
 The team must choose a suitable database to  manage and store substantial data for the food delivery application. 

## Decision

Start a thorough analysis of possible DBMS choices for the food delivery app, concentrating on MySQL in particular. Examine how well this choice works with the data structure of the app, and things like order histories, user accounts, and real-time updates.

## Consequences
We anticipate the following outcomes of our decision in using MySQL:

### Positive:
 - Effective transaction management, which is necessary for processing orders.
 - A strong community that supports the product's security features and proven dependability.
 - Scalability to handle increasing order volumes and user data.
### Negative:
 - Compatibility with the unique data structures used by the app, such as order histories and user accounts.
 

 


