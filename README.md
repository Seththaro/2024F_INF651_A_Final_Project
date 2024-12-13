Expense Tracker Application
===========================

This is a simple web-based expense tracker that allows users to track their spending, set category goals, visualize their expenses through charts, and manage their profile.

Features
--------

-   Track and categorize expenses.
-   Filter and sort expenses by date, category, or amount.
-   Visualize expenses using bar and pie charts.
-   Add and delete expenses.
-   Export expenses to CSV.
-   Manage user profile with the ability to upload a profile picture.
-   Responsive design for mobile and desktop devices.

Prerequisites
-------------

Before running the application, ensure you have the following installed:

-   A modern web browser (Chrome, Firefox, Safari, etc.)
-   No server-side dependencies required (static files only).

## File Structure

```plaintext
.
├── css/
│   ├── responsive.css
│   └── styles.css
├── images/
│   └── default-avatar.png
├── js/
│   ├── about.js
│   ├── contact.js
│   ├── home.js
│   ├── tracker.js
│   └── user.js
├── about.html
├── contact.html
├── index.html
├── tracker.html
└── user.html

```

### Explanation of Files

-   **`css/`**: Contains the styles for the application, including responsive design.

    -   `styles.css`: Main stylesheet for the application.
    -   `responsive.css`: Additional styles for mobile responsiveness.
-   **`js/`**: Contains JavaScript for managing the application's functionality.

    -   `about.js`: Handles logic for the About page.
    -   `contact.js`: Handles logic for the Contact page.
    -   `home.js`: Handles logic for the Home page.
    -   `tracker.js`: Manages expense tracking, category filtering, and CSV export.
    -   `user.js`: Manages user profile settings, including profile image and budget.
-   **`images/`**: Contains the default profile image for the user.

    -   `default-avatar.png`: Default avatar for users without a profile picture.
-   **`about.html`**:\
    The **About** page provides information about the application, including its purpose, how it works, and any other relevant details about the project.
-   **`contact.html`**:\
    This page contains a contact form, allowing users to send inquiries or feedback. It links to the `contact.js` script for handling form submission and validation.

-   **`index.html`**:\
The main page of the application, which serves as the landing page. It displays the overview of the app, a summary of user expenses, and links to other pages. It also includes the main navigation and dashboard features.

-   **`tracker.html`**:\
This page allows users to view and manage their expenses. It includes an expense tracking table, filtering options, charts for visualizing data, and the ability to add or delete expenses. The page is dynamically updated via JavaScript using `tracker.js`.

-   **`user.html`**:\
The user profile page where users can manage their personal information, set their budget, and upload a profile picture. It links to the `user.js` script to handle the profile data, including saving it to local storage.


How to Run the Application
--------------------------

1.  **Download or Clone the Repository**\
    If you don't have the project already, you can download or clone it to your local machine.

    To clone the repository, use:

    `git clone <https://github.com/Seththaro/2024F_INF651_A_Final_Project.git>`

2.  **Open the Application in a Web Browser**\
    The application is a static web app, so you don't need any backend setup. Simply open the `index.html` file in your web browser. You can do this by:

    -   Right-clicking the `index.html` file and selecting "Open with" your preferred browser.
    -   Alternatively, drag and drop the `index.html` file into the browser window.
3.  **Using the Application**\
    Once the app is open in the browser, you can:

    -   **Add Expenses**: Fill out the expense form and click submit to add expenses.
    -   **Filter Expenses**: Use the category filter to display expenses from specific categories.
    -   **Sort Expenses**: Click on the table header to sort expenses by date, category, or amount.
    -   **View Charts**: The application will display a bar chart and a pie chart showing the distribution of expenses by category.
    -   **Profile Management**: Manage your profile (name, email, budget, and profile picture) via the profile form.
    -   **Export to CSV**: Click the "Export to CSV" button to download a CSV file of your expenses.
