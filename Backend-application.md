## How to submit your work
- Email back to us a .zip file with the application
- Include any notes you think are relevant
  - What would you do if you had the whole week to complete this?
  - What would you do next?
  - What would you need to do before releasing this to a production environment? 
- Any feedback for us?
  - How was this test overall? I.e too hard, too easy, how long it took, etc

## Requirements
1. Create a client
    - All fields are required
2. Edit a client
    - All fields are required
3. Search for a client
    - Searching in the "search field" should filter the list of clients by their first or last name
    - Example: John Stevens and Steven Smith should both show up if a user searches "steven"
    - Example: John Stevens should show up if a user searches "john"

### Extra points
1. Emit an event after a client is created (so we can respond with side effects in the future)
    - You can mock a data store for events (you don't need to push it outside of this application - just pretend)

