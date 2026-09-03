# Todo List Application

✨ **A fully functional Todo List app with local storage, priority levels, and filtering**

## Features

### ✅ Core Functionality
- ➕ Add new tasks with priority levels (High, Medium, Low)
- ✔️ Mark tasks as completed
- 🗑️ Delete individual tasks
- 💾 Automatic local storage saving
- 🔄 Data persists across browser sessions

### 🎯 Filtering & Organization
- **All** - View all tasks
- **Active** - Show only incomplete tasks
- **Completed** - Show only finished tasks
- **High Priority** - Filter high-priority tasks only

### 📊 Statistics
- Total task count
- Active task count
- Completed task count
- Real-time updates

### 🎨 Beautiful UI
- Gradient backgrounds
- Smooth animations
- Responsive design (mobile & desktop)
- Interactive feedback
- Priority color coding

### 🧹 Maintenance
- Clear all completed tasks
- Clear all tasks at once
- Confirmation dialogs for destructive actions

## How to Use

1. **Add a Task**
   - Type your task in the input field
   - Select priority level (Low, Medium, High)
   - Click "+ Add" or press Enter

2. **Manage Tasks**
   - ✔️ Click checkbox to mark as complete
   - 🗑️ Click delete button to remove task
   - 🏷️ Tasks show priority level as colored badge

3. **Filter Tasks**
   - Click filter buttons at top
   - View tasks by status or priority

4. **Clean Up**
   - Click "Clear Completed" to remove finished tasks
   - Click "Clear All" to reset everything

## Technical Details

### Storage
- Uses HTML5 LocalStorage API
- Stores todos as JSON array
- Survives browser refresh and restart
- ~5MB storage limit per domain

### Data Structure
```javascript
{
  id: timestamp,
  text: "Task description",
  completed: false,
  priority: "high|medium|low",
  createdAt: "Date string"
}
```

### Browser Compatibility
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Technologies Used
- HTML5
- CSS3 (Gradients, Animations, Flexbox)
- Vanilla JavaScript (ES6)
- LocalStorage API

## Tips & Tricks

💡 **Keyboard Shortcuts**
- Press Enter to add a task
- Click checkbox for quick completion

🎯 **Priority Tips**
- Use **High** for urgent tasks
- Use **Medium** for regular tasks
- Use **Low** for nice-to-have items

📱 **Mobile Friendly**
- Responsive layout
- Touch-friendly buttons
- Optimized for small screens

## Live Demo

🚀 Play now: [Todo List App](https://hamdan36ame-maker.github.io/ravenix-game/todo.html)

---

**Enjoy organizing your tasks!** 🎉
