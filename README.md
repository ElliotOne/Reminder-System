# C# Windows Form Application: Reminder System

## Overview

Welcome to the Reminder System Windows Forms application! This tool helps you manage and track reminders in a simple and effective way. You can add, view, and delete reminders, with the ability to categorize them based on the due date.

## Features

### Add a New Reminder

- Reminder Title: Enter the title for your reminder.
- Reminder Description: Add a detailed description for the task.
- Due Date and Time: Set the date and time when the reminder is due.

Reminders are saved in a text file and displayed in a list. Each reminder is associated with a title, description, and due time.

### View Existing Reminders

- The application loads existing reminders from a text file and displays them in a list.
- Each item in the list shows the title, description, and due date of the reminder.

### Delete a Reminder

- You can delete reminders from the list by selecting them and clicking the "Delete" button.
- Reminders are removed both from the display and from the stored data in the text file.

### Reminder Status

- The status of each reminder is displayed based on whether the reminder's due date has passed or not:
  - Not Done Yet: If the reminder's due date has not passed.
  - Oops, You Forgot: If the reminder's due date has passed.

### UI Components
- Textboxes: For entering the reminder title and description.
- DateTimePicker: To set the reminder's due date and time.
- ListBox: Displays the list of all reminders.
- ErrorProvider: Shows error messages if title or description fields are empty.
- ToolTips: Provide real-time information about the status of each reminder.

### Data Storage
- All reminders are stored in a text file (ReminderData.txt).
- Each reminder is saved with the title, description, and due date in a |-separated format.

## How to Use

1. **Adding a New Reminder:**
   - Enter a title and description for your reminder.
   - Set a due date and time.
   - Click the "Add" button to save the reminder.
<img src="https://github.com/ElliotOne/Reminder-System/blob/master/screenshots/first.png"/>

2. **Viewing Reminders:**
   - The existing reminders will be displayed in the list. Each item shows the title, description, and due date.
<img src="https://github.com/ElliotOne/Reminder-System/blob/master/screenshots/second.png"/>

3. **Deleting a Reminder:**
   - Select the reminder you want to delete from the list.
   - Click the "Delete" button to remove it from the list and the text file.
<img src="https://github.com/ElliotOne/Reminder-System/blob/master/screenshots/third.png"/>

4. **Reminder Status:**
   - For each reminder, the application will display whether it is still pending or overdue.

Feel free to explore and manage your reminders efficiently with this easy-to-use Windows Forms application!
