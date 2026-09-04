# To-Do List Application

A beautiful, feature-rich to-do list application with local storage functionality.

## Features

✨ **Core Features:**
- Add, edit, and delete tasks
- Mark tasks as completed
- Set priority levels (Low, Medium, High)
- Filter tasks (All, Active, Completed, High Priority)
- Local storage persistence - your tasks are saved automatically
- Progress tracking with visual progress bar
- Task statistics (Total, Completed, Remaining)
- Responsive design - works on all devices

🎨 **UI/UX:**
- Beautiful gradient background
- Smooth animations and transitions
- Intuitive interface
- Mobile-friendly layout
- Visual priority indicators
- Task creation date and time tracking

💾 **Local Storage:**
- Automatic saving to browser local storage
- No server required
- Persistent data across browser sessions
- All tasks saved locally on your device

## How to Use

1. **Open** the `index.html` file in your web browser
2. **Add Task:** Type your task in the input field, select priority, and click "Add"
3. **Complete Task:** Click the checkbox to mark as completed
4. **Edit Task:** Click the edit icon to modify a task
5. **Delete Task:** Click the trash icon to remove a task
6. **Filter:** Use filter buttons to view All, Active, Completed, or High Priority tasks
7. **Clear:** Use quick action buttons to clear completed or all tasks

## File Structure

```
todo-list-app/
├── index.html      # Main HTML file
├── styles.css      # Styling and animations
├── app.js          # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with ES6 support

## Local Storage Details

- Tasks are stored in browser's localStorage under the key `todos`
- Maximum storage varies by browser (usually 5-10MB)
- Data persists until manually cleared
- Clearing browser history/cache may delete stored tasks

## Features Explained

### Priority Levels
- **Low:** Blue badge - less urgent tasks
- **Medium:** Orange badge - regular tasks
- **High:** Red badge - urgent tasks

### Filters
- **All:** Show all tasks
- **Active:** Show only incomplete tasks
- **Completed:** Show only completed tasks
- **High Priority:** Show only high-priority tasks

### Statistics
- **Total Tasks:** Count of all tasks
- **Completed:** Count of finished tasks
- **Remaining:** Count of incomplete tasks
- **Progress:** Percentage of completion

## Tips

- Press Enter to quickly add a task
- Tasks are saved automatically
- The progress bar shows your completion percentage
- Drag the scrollbar to see more tasks
- Click any filter button to organize your tasks

## License

Free to use and modify for personal or commercial projects.
