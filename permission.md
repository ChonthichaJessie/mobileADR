# Decision Record for Permission ADR
---
## Status
Approved
## Context
 The team is tasked with selecting a location tracking strategy for the food delivery app.  The objective is to show options that are close by, estimate delivery times, and make accurate suggestions. 

## Decision
Track the users whereabouts using the device's GPS capabilities. Only when the app is in use will the user's location be requested, and during onboarding, explicit consent will be requested. This choice is made in order to guarantee precise and up-to-date location data, improving the accuracy of delivery estimates and restaurant suggestions.

## Consequences
We anticipate the following outcomes and consequences of our decision:
### Easier:
- Easy onboarding with requests for specific permissions.
- Improved user experience because of accurate location information.
- Accurate restaurant suggestions and precise delivery times.
### Difficult:
- Adherence to location permission policies and updates specific to each platform.
- Potential privacy concerns raised by users

This decision was made because it carefully manages permissions to preserve the users privacy while placing high priority on location data accuracy.