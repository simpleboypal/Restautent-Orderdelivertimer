# Restautent-Orderdelivertimer ,day 1
This is the Restaurent website ,where the owner can know where the food is being prepared and what time the table is cooked upon

Bootstrap Enhancements
Card Component:

The app is wrapped in a card component with card-header, card-body, and card-footer.
Buttons:

Styled with Bootstrap classes (btn btn-primary, btn-success, btn-danger).
List Group:

Tasks are displayed using Bootstrap's list-group and list-group-item classes for a consistent layout.

How It Works
When the timer starts, the background color and progress bar update dynamically.
Colors guide the user:
Green (default) → Yellow (warning) → Red (critical).
The reset button resets the timer, progress bar, and colors to default.

Adding a Timer:

Each task now has a 30-second countdown timer.
A progress bar visually indicates the remaining time.
Timer Controls:

Start Timer: Begins the countdown for the specific task.
Reset Timer: Resets the countdown to 30 seconds.
Task Actions:

Complete: Marks the task as completed with a strikethrough.
Delete: Removes the task and clears the timer.
Visual Cues:

The progress bar turns red when 10 seconds remain.

Auto Movement of Tasks:

When the timer starts, the task moves from Pending to In Progress.
When the timer ends, the task automatically moves to Finished.
Color-Coded Status:

Tasks in Finished appear in light green.
The timer updates the task's background color (yellow, red) based on remaining time.
Simplified Buttons:

Start button triggers automatic movement between sections.
Delete button removes tasks.


Circular Timer Bar:

Timer uses a circular progress indicator.
Stroke color and progress change dynamically with remaining time.
Task Item Design:

Rounded corners, shadow effect, and color-coded background for statuses.
Interactive Buttons:

Start moves the task to "In Progress" and starts the timer.
Delete removes the task.
