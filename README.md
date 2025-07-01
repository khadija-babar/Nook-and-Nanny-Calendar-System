# Nook-and-Nanny-Calendar-System
The Nook and Nanny Calendar System is a dynamic calendar-based web application designed for a café or daycare setting. It helps manage daily staff tasks, attendance, sales, childcare tracking, salaries, expenses, and profit, all within a visually appealing and user-friendly interface.
The application includes four seasonal background videos (winter mp4, spring mp4, summer mp4, autumn mp4) that automatically change based on the month to enhance the visual experience.

## Key Features

1. Login with Role Access

   * Secure login system for multiple user roles: Manager, Barista, Cook, Kitchen Helper, Cleaner, Receptionist, and Nanny
   * Each user sees only the features and data relevant to their role

2. Interactive Calendar

   * Monthly calendar with buttons to navigate forward or backward
   * Highlights the current date
   * Marks days with scheduled tasks
   * Clicking a day allows managers to add or delete tasks or open the daily log

3. Full Daily Log Page

   * Opens a full-screen form to log:

     * Staff attendance
     * Number of drinks sold (Barista view)
     * Food sales (Cook and Kitchen Helper views)
     * Number of kids cared for (Nanny view)
     * Daily expenses like ingredients (Manager view)
   * Non-manager roles have read-only access
   * Managers can input, save, and edit all data

4. Automated Salary and Profit Calculation

   * Fixed monthly salaries per role
   * Nanny earns per child per day
   * Absence results in automatic salary deduction
   * Daily profit is calculated as:
     Profit = Total sales (drinks and food) minus Expenses, Nanny payments, and Absence deductions

5. Monthly Summary Panel

   * Displays the entire month's performance:

     * Number of days with data
     * Total kids cared for
     * Drink and food sales
     * Expenses
     * Role-wise attendance and salary
     * Net profit
   * Non-manager users see only their own stats

6. Data Storage and Recovery

   * All logs and tasks are saved in local storage
   * Data automatically loads when the app is reopened

7. Seasonal Background Videos

   * Seasonal video background changes based on current month
   * Designed for winter, spring, summer, and autumn
   * Enhances the user interface with visual elegance
