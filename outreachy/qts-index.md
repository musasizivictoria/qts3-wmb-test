# QuickStatements 3.0 - Home Page Documentation

## Welcome to QuickStatements 3.0

The homepage of QuickStatements 3.0 provides easy access to all major features and functionalities related to batch processing and user interaction. Below is an overview of the key components of the homepage and how to use them.

---

### Main Features

#### 1. **New Batch Button**
   - **Description**: This button takes you to the page where you can create a new batch of statements.
   - **Location**: It's placed within the main content area of the homepage.
   - **Style**: The button is styled with a custom blue theme (`background-color: blue` and `color: white`).
   - **Action**: Clicking the button navigates the user to the "New batch" creation form.

#### 2. **Batch Search Form**
   - **Description**: This form allows users to search for a specific batch by providing its batch ID.
   - **Form Fields**:
     - **Batch ID** (required): A numerical input where users can enter the batch ID.
   - **Action**: Clicking the "See batch details" button will submit the form to search and display details of the specific batch.

#### 3. **User Batch Search Form**
   - **Description**: This form allows users to search for batches created by a specific user by entering the username.
   - **Form Fields**:
     - **Username** (required): A text input where users can enter the username to view all associated batches.
   - **Action**: Clicking the "See batches by user" button will submit the form to search and display batches created by the specified user.

---

### Navigation Menu

The navigation bar provides links to various pages and features:

- **QuickStatements 3.0**: The title link that brings you back to the homepage.
- **New Batch**: A direct link to the "New batch" creation page.
- **Last Batches**: A placeholder link that could be used to navigate to a page showing recently created batches (currently without a destination).
- **GitHub Repository**: A link to the official [QuickStatements 3.0 GitHub repository](https://github.com/WikiMovimentoBrasil/quickstatements3), where the codebase is maintained.

For authenticated users:
- **User**: Displays the username of the logged-in user.
- **Your Last Batches**: Provides a link to view the most recent batches created by the logged-in user.

For anonymous users:
- **Login**: A link for users to log in to their account.

---

### Batch Creation Form

The "New batch" page allows users to create a batch of statements. Here's how it works:

#### Form Fields:

1. **Command Format**:
   - Users can select the command format from two options:
     - `V1`: A command-line format.
     - `CSV`: A CSV file format.

2. **Batch Name**:
   - An optional field where users can provide a custom name for the batch.

3. **Commands**:
   - A large text area where users can input commands or data for the batch.
   - The commands can be pasted or manually written in the chosen format.

#### Submit Button:
- Clicking the "Execute" button will process the batch creation based on the provided input.

#### Error Handling:
- If there's an error (e.g., missing or incorrect input), a red error message will be displayed at the top of the form to notify the user.

---

### Additional Information

#### CSS and HTMX Integration
- **CSS**: The homepage uses the Pico CSS framework to ensure a minimalist and responsive design. It also loads custom styles to modify button colors and other elements.
- **HTMX**: HTMX is included to handle dynamic interactions such as form submissions and updating content without refreshing the page.

---

This concludes the overview of the QuickStatements 3.0 home page features. Each component provides functionality to make batch processing of data easier and more efficient for users.
