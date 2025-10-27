# Todo Application

A simple, responsive todo list application built with HTML, CSS, and JavaScript. This application allows users to create, manage, and save their tasks in a clean and intuitive interface.

## Features

- Create new tasks
- Save tasks to local storage
- Responsive design that works on desktop and mobile devices
- Clean and intuitive user interface
- Bootstrap-based styling for modern appearance

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 4.5.2
- jQuery 3.5.1
- Popper.js 1.16.1
- Local Storage API

## Storage Mechanism

This application uses the browser's Local Storage API for data persistence. Here's why Local Storage is significant for this application:

### What is Local Storage?
- Local Storage is a web storage solution that allows websites to store key-value pairs locally within a user's browser
- Data stored in Local Storage persists even after the browser window is closed
- Each domain gets its own separate storage area

### Benefits of Local Storage in this Todo App:
- **Data Persistence**: Tasks remain saved even after browser restart
- **Offline Access**: Users can view their todos without an internet connection
- **No Server Required**: Works completely client-side without needing a backend
- **Performance**: Instant data access without server requests
- **Storage Capacity**: Can store up to 5-10 MB of data (varies by browser)
- **User Privacy**: Data stays on the user's device

### How it's implemented:
- Tasks are saved automatically when clicking the "Save" button
- Data is stored in JSON format for easy parsing
- Todos are loaded automatically when the page opens
- Clear browser data/cache will remove stored todos

## Project Structure

```
Todo_Application/
├── index.html     # Main HTML file
├── index.css      # Styles for the application
├── index.js       # JavaScript functionality
└── README.md      # Project documentation
```

## Getting Started

1. Clone the repository or download the files
2. Open `index.html` in your web browser
3. Start adding your todos!

## Usage

1. Type your task in the input field
2. Click "Add" button or press Enter to add the task to your list
3. Click "Save" button to persist your tasks in local storage
4. Your tasks will be automatically loaded when you reopen the application

## Browser Support

The application works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Git Setup Template

Follow these steps to set up a new project with Git and GitHub:

### First-time Git Setup (if never done before)
```bash
# Set your global Git username
git config --global user.name "Your Name"

# Set your global Git email
git config --global user.email "your.email@example.com"
```

### New Project Setup
1. Create a new repository on GitHub
   - Go to github.com
   - Click "New repository"
   - Name your repository
   - Choose public/private
   - Don't initialize with README if you have existing code

2. Initialize local repository
```bash
# Navigate to your project directory
cd your-project-directory

# Initialize a new Git repository
git init

# Add all files to Git
git add .

# Create initial commit
git commit -m "Initial commit: Project description"

# Add GitHub repository as remote
git remote add origin https://github.com/username/repository-name.git

# Push to GitHub
git push -u origin main
```

### Common Git Commands
```bash
# Check repository status
git status

# View commit history
git log --oneline

# Create and switch to new branch
git checkout -b feature-name

# Switch branches
git checkout branch-name

# Pull latest changes
git pull origin main

# Push changes
git push origin branch-name
```

### Best Practices
1. Create meaningful commit messages
2. Create a new branch for each feature
3. Pull latest changes before starting new work
4. Review changes before committing
5. Add appropriate .gitignore file
6. Test code before pushing

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).