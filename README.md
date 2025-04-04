
Built by https://www.blackbox.ai

---

```markdown
# DreamLottery

## Project Overview
DreamLottery is a web-based lottery platform where users can join various lottery contests, manage their accounts, and view trending lottery events. The application features a modern and responsive user interface, leveraging Tailwind CSS for styling and Font Awesome for icons.

## Installation

To run the DreamLottery application locally, follow the steps below:

1. **Clone the repository:**
   ```bash
   git clone https://your-repo-url.git
   cd DreamLottery
   ```

2. **Open the project in your preferred web browser:**
   You can open `index.html`, `signup.html`, or `login.html` directly in your browser, or you can set up a local server to serve the files.

## Usage

1. Navigate to `index.html` to view the lottery options.
2. Click on the "Join Now" button to participate in any lottery contest.
3. If you are a new user, navigate to `signup.html` to create an account by filling in the required details.
4. If you already have an account, go to `login.html`, enter your mobile number and password to access your account.

## Features

- User account creation and management
- Multiple lottery options to join with associated prizes
- Trending notifications about upcoming lottery draws and bonuses
- Responsive design that adapts to various screen sizes
- Password strength indicator during signup

## Dependencies

DreamLottery utilizes the following dependencies:

- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Font Awesome](https://fontawesome.com/) for icons

The dependencies are included via CDN links in the HTML files.

## Project Structure

```plaintext
DreamLottery/
│
├── index.html        # Home page for the lottery
├── signup.html       # User signup page
├── login.html        # User login page
└── styles/
    └── custom.css    # Custom CSS styles (if any)
```

### Additional Details

- The project does not have a backend as of now; hence, the form submissions lead to regular page navigation (no real authentication).
- The application uses local strategies to enhance user experience but does not store any user data.

For any issues or feature suggestions, please feel free to raise an issue in this repository.
```