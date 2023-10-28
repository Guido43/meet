# Meet
## A meet-up application
This is the project achievement 4 meet-up application.
# Specifics
Meet is a serverless, progressive web application (PWA) built with React using a test-driven development (TDD) technique. The application uses the Google Calendar API to fetch upcoming events.

## Features
### 1. Filter Events By City
Given: The User has opened the application corectly and has navigated to the search-bar feature and has view the drop-down menu regarding an available location.
When: The User clicks on a city location which is available in this drop-down menu.
Then: The events listed for that city will appear on the page and the user will be able to view their relevant details. 

### 2. Show/Hide Event Details
Given: The user is viewing the 'Event-Details' of the previously chosen city location.
When: The user clicks on a 'Show Details' button. 
Then: the container expands showing more of the details for that specific event. The user then has the option to 'Hide Details' in order to return to the previous state.

### 3. Specify Number of Events
Given: The user is viewing the 'Event-Details' of a selected location.
When: The user selects a number-range of events to be listed for that location.
Then: The events will be displayed in order and will meet the required amount of events desired to be shown by the user.

### 4. Use App When Offline
Given: The app has been correctly installed and used whilst the user was online.
When: The user is offline, or specifies that they wish to use the application offline in the settings option for the application.
Then: The user will be able to still use the application whilst offline, albeit with some limitations regarding new data drawn from online resources.

### 5. Add an App Shortcut To The Home Screen
Given: The user has installed the app correctly and wishes to use it on a moblie device.
When: The user holds down on the app's icon.
Then: The application offers the option to add a shortcut icon to the mobile device's home screen.

### 6. Display Charts Visualizing Event Details
Given: The user is viewing the 'Event-Details' of a specific location.
When: The user clicks on the option to show 'statistics' for the chosen specific location.
Then: Statistical charts and diagrams are revealed, showing data-visualization for events concerning that location in comparison to other available locations.


## Elements particular to this application
Serverless: No backend maintenance, easy to scale, always available, no cost for idle time.
PWAs: Instant loading, offline support, push notifications, “add to home screen” prompt.
responsive design, and cross-platform compatibility.
