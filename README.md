# Appointy

**Appointy** is a comprehensive appointment scheduling and reminder application designed to help users stay organized and manage their events efficiently. It features a user-friendly interface, seamless integration with Google Calendar, and various tools to enhance productivity.

---

## **Project Structure**
The project is organized as follows:

- **Home Page**
- **Login Page**
- **Calendar Page**
- **Google Calendar Integration**
- **Methods Implemented**
- **Getting Started**
- **Conclusion**

---

## **Technologies Used**

- **HTML**: For structuring web pages.
- **CSS**: For styling the application.
- **JavaScript**: For adding interactivity and functionality.
- **Google Calendar API**: For integrating Google Calendar features.

---

## **Features**

### **Home Page**
The home page provides an overview of the application's features, including:

- **Popular Features**: Highlights key functionalities like cloud connectivity, event planning, live feed, and more.
- **Client Feedback**: Displays testimonials from users.
- **Rewards**: Information about rewards and discounts.
- **Developers**: Details about the development team.

### **Login Page**
The login page enables users to log in or create a new account. It includes:

- Fields for **email/phone number** and **password**.
- Account creation options.

### **Calendar**
The **calendar page** is the core feature of the application, allowing users to:

- View, add, and manage events.
- Navigate between months.
- View events for specific days.
- Add new events with an interactive interface.

### **Google Calendar Integration**

The application integrates with **Google Calendar**, allowing users to:

- Authorize their account.
- Sync events with their Google Calendar.

---

## **Methods Implemented**

### **Calendar Methods**

- `initCalendar`: Initializes the calendar with the current month and year.
- `prevMonth`: Navigates to the previous month.
- `nextMonth`: Navigates to the next month.
- `addListener`: Adds event listeners to calendar days.
- `getActiveDay`: Retrieves the active day and updates event details.
- `updateEvents`: Updates events for the active day.
- `addEvent`: Adds a new event to the calendar.
- `deleteEvent`: Removes an event from the calendar.
- `saveEvents`: Saves events to local storage.
- `getEvents`: Retrieves events from local storage.

### **Google Calendar API Methods**

- `gapiLoaded`: Callback executed after the Google API loads.
- `initializeGapiClient`: Initializes the Google API client.
- `gisLoaded`: Callback executed after Google Identity Services load.
- `handleAuthClick`: Handles the authorization click event.
- `handleSignoutClick`: Manages the sign-out process.
- `listUpcomingEvents`: Fetches upcoming events from Google Calendar.

---

## **Getting Started**

To get started with **Appointy**, follow these steps:

1. **Clone the repository**.
2. **Open the project** in **Visual Studio Code**.
3. Open `index.html` in the **HomePage** directory to view the home page.
4. Navigate to the **Login** directory to access the login page.
5. Navigate to the **Calendar** directory to access the calendar page and integrate with Google Calendar.

---

## **Conclusion**

**Appointy** is a powerful tool for managing appointments and reminders. With its intuitive interface and robust features, it helps users stay organized and productive. The integration with **Google Calendar** further enhances its functionality, making it a valuable addition to any user’s toolkit.
