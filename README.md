LunaCare: Your Personalized Period & Fertility Tracker

LunaCare is a comprehensive web-based application designed to help individuals track their menstrual cycles, predict fertile windows, log symptoms, and gain insights into their reproductive health.

Table of Contents

  - [Features](https://www.google.com/search?q=%23features)
  - [How to Use](https://www.google.com/search?q=%23how-to-use)
  - [Project Structure](https://www.google.com/search?q=%23project-structure)
  - [Technologies Used](https://www.google.com/search?q=%23technologies-used)

Features

LunaCare offers the following key features:

Period & Fertility Tracking (INDEX.HTML):

      Hero Section: Welcoming display for the Period & Fertility Tracker with a compelling subtitle.
      About Section: Provides information about the tracker's purpose and benefits.
      Call to Action: Encourages users to "Get Started Today" and leads to the signup/login modal.
      Feature Cards: Highlights core functionalities:
          * Menstrual Cycle Tracking: Log periods, flow intensity, and track irregularities.
          * Pregnancy Symptoms Log: Monitor early pregnancy signs and physical sensations.
          * Fertile Window Prediction: Accurately predict ovulation and fertile windows for family planning.
       Cookie Consent Banner: Informs users about cookie usage and provides an "Accept" button.
      Login/Signup Modal: A modal window for user authentication, allowing users to switch between login and signup forms.

Advanced Cycle & Wellness Tracker (Cycle-Tracker.html):

      Personalized Cycle Insights: Displays current day in cycle, next period and ovulation dates.
      Daily Insight: Provides phase-specific information and tips (e.g., Period, Follicular, Fertile, Ovulation, Luteal).
      Detailed Phase Dates: Presents predicted start and end dates for each cycle phase (Period, Follicular, Fertile Window, Ovulation Day, Luteal Phase).
      Cycle Overview: Summarizes key cycle metrics like cycle length, period duration, and upcoming dates.
      Body & Cycle Information: Offers general information about what to expect during each cycle phase.
      Saved Notes & Symptoms: Displays previously saved notes and logged symptoms.
      Back to Dashboard Link: Navigates back to the main LunaCare dashboard.

LunaCare Dashboard (LunaCare.html):

      User-Friendly Interface: A clean and intuitive dashboard for managing cycle information.
      Cycle Information Input: Allows users to input their last period start date, typical cycle length, and period duration.
      Dynamic Predictions: Calculates and displays:
          * Next Period Date and days remaining.
          * Estimated Ovulation Date.
          * Fertile Window (start and end dates).
          * Current Cycle Phase.
      Symptom Tracker: A comprehensive list of common symptoms that users can select to log. Saved symptoms are displayed.
      Cycle Notes: A free-text area for users to record personal observations, mood changes, or any other relevant notes.
      Local Storage: All user input (last period date, cycle length, period duration, symptoms, and notes) is saved locally in the browser's `localStorage` for persistent access.
      Loading Spinner: Provides visual feedback during data processing.

How to Use

1.  Open `INDEX.HTML`: Start by opening the `INDEX.HTML` file in your web browser. This is the landing page.
2.  Accept Cookies: A cookie consent banner will appear at the bottom. Click "Accept" to dismiss it.
3.  Get Started / Login / Signup:
      * Click the "Get Started Today" button.
      * The Login/Signup modal will appear. You can switch between "Log In" and "Sign Up" tabs.
      * For this demonstration, simply fill in the details for either login or signup (passwords for signup must match).
      * Upon successful "login" or "signup" (simulated client-side), you will be redirected to `LunaCare.html`.
4.  LunaCare Dashboard (`LunaCare.html`):
      * Input Cycle Data: Enter your "Last Period Start" date, "Cycle Length (days)", and "Period Duration (days)".
      * Update Predictions: Click "Update Predictions" to see your personalized cycle overview.
      * Log Symptoms: Check the boxes next to any symptoms you are experiencing.
      * Add Notes: Type any relevant notes into the "Cycle Notes" text area.
      * Save Data: Click "Save Symptoms" or "Save Notes" to store your data locally. Data is also auto-saved after 2 seconds of inactivity in the notes field, and when "Update Predictions" is clicked.
5.  View Detailed Cycle Insights (`Cycle-Tracker.html`)**:
      * From the `LunaCare.html` dashboard, click the "Update Predictions" button. This will redirect you to `Cycle-Tracker.html`, which provides a more detailed breakdown of your current cycle phase and predictions.
      * Click "Back to Dashboard" to return to `LunaCare.html`.

Project Structure

.
├── INDEX.HTML
├── LunaCare.html
└── Cycle-Tracker.html

  * `INDEX.HTML`: The landing page with an overview of the tracker and the login/signup functionality.
  * `LunaCare.html`: The main dashboard for inputting and viewing cycle predictions, logging symptoms, and adding notes.
  * `Cycle-Tracker.html`: Provides detailed insights into the current cycle phase and predictions based on the data entered in `LunaCare.html`.

Technologies Used
HTML5: Structure of the web pages.
CSS3: Styling for a modern and responsive design.
Tailwind CSS: (Used in `LunaCare.html` and `Cycle-Tracker.html`) A utility-first CSS framework for rapid UI development.
JavaScript: Core logic for cycle calculations, data storage (localStorage), dynamic content updates, and user interaction.
Google Fonts (Poppins, Inter): For enhanced typography.
Font Awesome: (Used in `Cycle-Tracker.html`) For icons.
