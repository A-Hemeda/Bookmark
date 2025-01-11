# Bookmark Manager

Bookmark Manager is a user-friendly web application that allows users to save, manage, and organize their favorite websites. Built with HTML, CSS, and JavaScript, the application is lightweight and offers a simple yet effective way to manage bookmarks.

## Features

- **Add Bookmarks:** Save your favorite websites with their names and URLs.
- **View Bookmarks:** Display a list of saved bookmarks in a clean and organized layout.
- **Edit Bookmarks:** Update the details of any saved bookmark.
- **Delete Bookmarks:** Remove unwanted bookmarks with a single click.
- **Visit Bookmarks:** Open saved links directly in a new browser tab.
- **Validation:** Ensure URLs are valid before saving bookmarks.

## Usage

1. **Add a Bookmark**
   - Enter the website name and URL in the provided input fields.
   - Click the "Add Bookmark" button to save it to your list.

2. **View Bookmarks**
   - Your saved bookmarks will appear in a list below the input fields.

3. **Edit or Delete Bookmarks**
   - Use the "Edit" button to modify a bookmark's details.
   - Click the "Delete" button to remove a bookmark from the list.

4. **Visit Bookmarks**
   - Click on the name of any bookmark to open the website in a new tab.

5. **Validation**
   - Ensure the URL starts with "http://" or "https://" before saving.

## Code Overview

### Global Variables
- `bookmarkForm`: Form element used for adding new bookmarks.
- `bookmarkNameInput`, `bookmarkUrlInput`: Input fields for the name and URL of the bookmark.
- `bookmarkList`: Container element for displaying the list of bookmarks.
- `bookmarks`: Array to store all saved bookmarks.

### Events

- **Form Submission**
  - Listens for the form's submit event to save a new bookmark.

- **Edit and Delete Buttons**
  - Dynamically generated buttons for each bookmark to allow editing or deletion.

### Functions

- **`addBookmark`**
  - Adds a new bookmark to the list and updates the UI.

- **`displayBookmarks`**
  - Renders all saved bookmarks in the list.

- **`deleteBookmark`**
  - Removes a bookmark from the list and updates the UI.

- **`validateInput`**
  - Ensures that the URL and name fields are not empty and that the URL is valid.

## Live Demo

Experience the Bookmark Manager in action! Click the link below to access the live demo:

### [Live Demo](https://a-hemeda.github.io/Bookmark/)

Feel free to explore the features, organize your bookmarks, and simplify the way you manage your favorite websites.

## Contributing

If you have suggestions, find any issues, or want to enhance the application, feel free to open an issue or submit a pull request. Contributions are always welcome!
