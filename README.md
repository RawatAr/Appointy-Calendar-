Appointy
Appointy is a comprehensive appointment scheduling and reminder application designed to help users stay organized and manage their events efficiently. The application features a user-friendly interface, seamless integration with Google Calendar, and various tools to enhance productivity.

Technologies Used
HTML: For structuring the web pages.
CSS: For styling the application.
JavaScript: For adding interactivity and functionality.
Google Calendar API: For integrating Google Calendar features.
Features
Home Page
The home page provides an overview of the application's features and includes sections such as popular features, client feedback, rewards, and information about the developers.

Popular Features: Highlights key features like cloud connectivity, event planning, live feed, and more.
Client Feedback: Displays testimonials from clients.
Rewards: Information about rewards and discounts.
Developers: Information about the development team.
Login Page
The login page allows users to log in to their accounts or create a new account. It includes fields for email/phone number and password.

Calendar
The calendar page is the core feature of the application. It allows users to view, add, and manage events. The calendar is interactive and provides functionalities such as navigating between months, viewing events for a specific day, and adding new events.

Google Calendar Integration
The application integrates with Google Calendar, allowing users to authorize and sync their events with their Google Calendar account.

Methods Implemented
Calendar Methods
initCalendar: Initializes the calendar with the current month and year.
prevMonth: Navigates to the previous month.
nextMonth: Navigates to the next month.
addListner: Adds event listeners to the calendar days.
getActiveDay: Gets the active day and updates the event details.
updateEvents: Updates the events for the active day.
addEvent: Adds a new event to the calendar.
deleteEvent: Deletes an event from the calendar.
saveEvents: Saves events to local storage.
getEvents: Retrieves events from local storage.
Google Calendar API Methods
gapiLoaded: Callback after the Google API is loaded.
initializeGapiClient: Initializes the Google API client.
gisLoaded: Callback after Google Identity Services are loaded.
handleAuthClick: Handles the authorization click event.
handleSignoutClick: Handles the sign-out click event.
listUpcomingEvents: Lists the upcoming events from Google Calendar.
Getting Started
To get started with Appointy, follow these steps:

Clone the repository.
Open the project in Visual Studio Code.
Open the index.html file in the HomePage directory to view the home page.
Navigate to the Login directory to access the login page.
Navigate to the Calendar directory to access the calendar page and integrate with Google Calendar.
Conclusion
Appointy is a powerful tool for managing appointments and reminders. With its intuitive interface and robust features, it helps users stay organized and productive. The integration with Google Calendar further enhances its functionality, making it a valuable addition to any user's toolkit.
