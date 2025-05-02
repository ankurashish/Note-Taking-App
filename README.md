
# Note App with Theme Toggle

This is a simple Note App that allows users to add, delete, and view notes stored in the browser's `localStorage`. It also features a theme toggle button that lets users switch between **dark mode** and **light mode** using a stylish toggle switch.

## Features

- **Add Notes**: Users can input their notes which are saved in the browser’s `localStorage`.
- **Delete Notes**: Users can delete notes stored in `localStorage`.
- **Theme Toggle**: Switch between dark mode and light mode using a toggle switch. The toggle updates the appearance of the page, changing the background and text color.

## Technologies Used

- **HTML** for the structure of the page.
- **CSS** for styling the page, including the theme toggle switch and dark/light mode styles.
- **JavaScript** for the functionality of adding, deleting, and displaying notes, as well as handling the theme toggle.

## How to Use

### 1. Add a Note
- Click the **"Add Note"** button.
- A prompt will appear asking you to input your note.
- The note will be saved in `localStorage` and displayed on the page.

### 2. Delete a Note
- Click the **"Delete Note"** button.
- A confirmation dialog will appear asking if you're sure you want to delete the note.
- If confirmed, the note will be removed from `localStorage`, and the content will be cleared from the page.

### 3. Toggle Theme
- Click the **toggle switch** (located below the note section) to switch between dark mode and light mode.
- The background color and text color will change based on the selected theme.
- Dark mode has a black background with white text.
- Light mode has a light background with black text.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/note-app-with-theme-toggle.git
   ```

2. Navigate to the project directory:
   ```bash
   cd note-app-with-theme-toggle
   ```

3. Open the `index.html` file in your browser to see the app in action.

## Example Screenshot

Here's an example of how the app looks:

![Note App Screenshot](https://via.placeholder.com/600x400.png)

## Future Improvements

- **Multiple Notes**: Currently, the app only supports one note at a time. Future versions could allow users to add multiple notes, each with a title and content.
- **Persistent Theme**: The theme preference (dark or light mode) could be stored in `localStorage` so that the theme persists across page reloads.
- **Mobile Responsiveness**: The layout could be improved for better responsiveness on mobile devices.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
