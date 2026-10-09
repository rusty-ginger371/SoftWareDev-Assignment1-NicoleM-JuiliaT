# SoftWareDev-Assignment1-NicoleM-JuiliaT

This is a simple event planner application written in Javascript using MERN stack.

Created By:   
Nicole Masters - rusty-ginger371  
Julia Trueman - Snickers6077  

### Requirement Cards:

#### Requirement ID - FR-01  
Requirement Name - Create New Events  
User/Actor - Event Goer  
Requirement Statement - Users need to be able to create new events. events include an event name, date/time, description, event id.  
Priority - Must have  
Acceptance Criteria - If the entered information is valid, a new event should be created and displayed on the dashboard when the user clicks create event  
Related SDLC Stage - Requirements Analysis  

#### Requirement ID - FR-02
Requirement Name - Dashboard to View Events  
User/Actor - Event Planner  
Requirement Statement - The app should have a dashboard homepage where all events are viewable in cards  
Priority - Must have  
Acceptance Criteria - Must display all event cards that are currently active, default sorting method is by date (closest to furthest away)  
Related SDLC Stage - Requirement Analysis

#### Requirement ID - FR-03
Requirement Name - Edit Event Cards  
User/Actor - Event goer  
Requirement Statement - User should be allowed to edit the name, date, description and header image of the event cards.  
Priority - Must Have
Acceptance Criteria - Assuming edited changes are valid, the new info is properly saved and displayed on the card. If the edited changes are not valid, a user friendly error message should be thrown.  
Related SDLC Stage - Requirements Analysis  

#### Requirement ID - FR-04  
Requirement Name - Remove Events  
User/Actor - Event goer  
Requirement Statement - User should have the ability to delete or remove event cards from the dashboard  
Priority - Must Have  
Acceptance Criteria - The event card is properly removed from the dashboard and information is discarded  
Related SDLC Stage - Requirements Analysis  

#### Requirement ID - FR-05  
Requirement Name - Sort Events Manually  
User/Actor - Events planner  
Requirement Statement - Users should be able to manually sort events by selecting the “manual sort” sort option on the side of the screen, and clicking and dragging the card to where they want.  
Priority - Should Have  
Acceptance Criteria - When the card is dragged it is assigned a priority number, that number is stored and remembered whenever the user opens the app again.  
Related SDLC Stage - Requirements Analysis  

#### Requirement ID - FR-06
Requirement Name - Calendar view  
User/Actor - Event goer  
Requirement Statement - User should be able to see an alternate view of the dashboard that shows all their events in a calendar view.  
Priority - Could have
Acceptance Criteria - Calendar should display a shortened version:of the event cards on the day that their date corresponds with.
Related SDLC Stage - Requirements Analysis

For our branching workflow, I (Julia) added the first 3 requirement cards and created a separate branch when committing it that I then merged to the main branch. Then, Nicole added the next two requirement cards and created a separate branch that was then successfully merged with the main branch. After that we both tried to create pull requests that updated the same lines of code (47 and 48) and resolved a conflict by keeping the initial change made to the card.  
Using github for canary development, the last stable version of the project could be kept on a the main branch while the working version would stay on it's own branch until it is properly tested and the bugs have been handled. Only then could it be merged to the main branch.

