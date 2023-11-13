# Meet
## A meet-up application
This is the project achievement 4 meet-up application.
# Specifics
Meet is a serverless, progressive web application (PWA) built with React using a test-driven development (TDD) technique. The application uses the Google Calendar API to fetch upcoming events.

## Features
### 1. Filter Events By City
User Story: As a user, I would like to be able to filter events by city so that I can see the list of events that take place in that city.

Given: The User has opened the application corectly and has navigated to the search-bar feature and has view the drop-down menu regarding an available location.

When: The User clicks on a city location which is available in this drop-down menu.

Then: The events listed for that city will appear on the page and the user will be able to view their relevant details. 

### 2. Show/Hide Event Details
User Story: As a user, I would like to be able to show/hide event details so that I can see more/less information about an event.

Given: The user is viewing the 'Event-Details' of the previously chosen city location.

When: The user clicks on a 'Show Details' button. 

Then: the container expands showing more of the details for that specific event. The user then has the option to 'Hide Details' in order to return to the previous state.

### 3. Specify Number of Events
User Story: As a user, I would like to be able to specify the number of events I want to view in the app so that I can see more or fewer events in the events list at once.

Given: The user is viewing the 'Event-Details' of a selected location.

When: The user selects a number-range of events to be listed for that location.

Then: The events will be displayed in order and will meet the required amount of events desired to be shown by the user.

### 4. Use App When Offline
User Story: As a user,I would like to be able to use the app when off line so that I can see the events I viewed the last time I was online.

Given: The app has been correctly installed and used whilst the user was online.

When: The user is offline, or specifies that they wish to use the application offline in the settings option for the application.

Then: The user will be able to still use the application whilst offline, albeit with some limitations regarding new data drawn from online resources.

### 5. Add an App Shortcut To The Home Screen
User Story: As a user, I would like to be able to add the app shortcut to my home screen so that I can open the app faster.

Given: The user has installed the app correctly and wishes to use it on a moblie device.

When: The user holds down on the app's icon.

Then: The application offers the option to add a shortcut icon to the mobile device's home screen.

### 6. Display Charts Visualizing Event Details
User Story: As a user, I would like to be able to see a chart showing the upcoming events in each city so that I know what events are organized in which city.

Given: The user is viewing the 'Event-Details' of a specific location.

When: The user clicks on the option to 'show statistics' for the chosen specific location.

Then: Data Visualization charts (2) are revealed, showing data-visualization for events concerning that location in comparison to other available locations.


## Elements particular to this application
Serverless: No backend maintenance, easy to scale, always available, no cost for idle time.
PWAs: Instant loading, offline support, push notifications, “add to home screen” prompt.
responsive design, and cross-platform compatibility.

## Serverless Functionality
The serverless functions coded into the application result in no need for constant maintenance of the application as it draws its information directly from Google's Calendar application, the information therefore will also always be relevant and up-to-date. The application will also always be available and uses AWS as its serverless platform, therefore also making it easy to scale. As the serverless functionality executes the serverless functions in the application only on user demand per a pay-as-you-go system, there are low online costs resulting as when the application remains idle no costs are incurred.
