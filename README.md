# Calendar App

This is a simple and interactive calendar application built using HTML, CSS, and JavaScript. The app allows users to view dates, navigate between months, and add/delete events for specific days. The calendar is designed to be responsive and user-friendly, with a clean and modern interface.

---

## Features

- **View Calendar**: Display the current month with highlighted today's date.
- **Navigate Months**: Move between previous and next months using arrow buttons.
- **Go to Specific Date**: Jump to a specific month and year using the "Go" button.
- **Add Events**: Add events with a title, start time, and end time for any day.
- **Delete Events**: Remove events by clicking on them and confirming the deletion.
- **Persistent Events**: Events are saved in the browser's local storage and persist even after refreshing the page.
- **Responsive Design**: The app is designed to work seamlessly on both desktop and mobile devices.

---

## How to Use

1. **Navigate the Calendar**:
   - Use the `<` and `>` buttons to move between months.
   - Click the "Today" button to return to the current date.

2. **Add an Event**:
   - Click the `+` button at the bottom right to open the "Add Event" form.
   - Fill in the event title, start time, and end time.
   - Click "Add Event" to save the event.

3. **View Events**:
   - Click on any day to view its events in the right panel.
   - Events are displayed with their title and time.

4. **Delete an Event**:
   - Click on an event in the right panel to delete it.
   - Confirm the deletion when prompted.

5. **Jump to a Specific Date**:
   - Enter a date in the format `mm/yyyy` in the input field.
   - Click the "Go" button to navigate to that month and year.

---

## File Structure

- `index.html`: The main HTML file containing the structure of the calendar app.
- `style.css`: The CSS file for styling the calendar and its components.
- `script.js`: The JavaScript file for handling the calendar logic, event management, and local storage.

---

## Technologies Used

- **HTML5**: For structuring the calendar and event components.
- **CSS3**: For styling the app, including animations and responsive design.
- **JavaScript**: For handling calendar navigation, event management, and local storage.
- **Font Awesome**: For icons used in the app (e.g., arrows, plus button).
- **Google Fonts**: For the `Montserrat` and `Inter` fonts used in the app.

---

## Installation

1. Clone the repository or download the source code.
2. `` git clone https://github.com/bontlenkoale1/Calendar-with-todo-list ``
3. Open the `index.html` file in your browser.
4. Start using the calendar app!

---

## Customization

- **Change Colors**: Modify the `--primary-color` variable in the `:root` selector in `style.css` to change the theme color.
- **Add More Fonts**: Replace the Google Fonts link in the `<head>` section of `index.html` with your preferred fonts.
- **Adjust Layout**: Modify the `container`, `left`, and `right` classes in `style.css` to adjust the layout.

---

## Acknowledgments

- Thanks to [Font Awesome](https://fontawesome.com/) for the icons.
- Thanks to [Google Fonts](https://fonts.google.com/) for the fonts used in this project.

---

Enjoy using the Calendar App! 🗓️
