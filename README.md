# Kaam Kaji List
> A powerful task management application for organizing and tracking your daily tasks and productivity.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

Kaam Kaji List is a modern, intuitive task management application designed to help you stay organized and productive. Built with React Native, it provides a sleek dark-themed interface that allows users to effortlessly add, track, and manage their tasks across different stages of completion.

The app enables users to create tasks, mark them as complete, and delete them as needed. With a clean, minimalist design and powerful functionality, Kaam Kaji List transforms task management into a smooth, enjoyable experience.

![](header.png)

## Installation
OS X & Linux:
```sh
npm install kaam-kaji-list --save
```
Windows:
```sh
npm install kaam-kaji-list --save
```

## Usage Example
Create and manage your tasks with ease:

```javascript
// Add a new task
addTask('Complete project report', '2024-02-15')

// Toggle task completion
toggleTaskCompletion(taskId)

// Delete a task
deleteTask(taskId)
```

*For more examples and usage, please refer to the [Wiki][wiki].*

## Features
- Dark theme user interface
- Add tasks with optional deadlines
- Mark tasks as complete
- Delete tasks
- Separate lists for active and completed tasks
- Responsive design
  
<p align="center">
  <img src = "https://github.com/user-attachments/assets/35a8ce97-56e1-45f1-95e0-d48429bd9f7c" width=300>
</p>
<p align="center">
  <img src = "https://github.com/user-attachments/assets/45dfd217-cc54-4981-958d-00258e225f72" width=300>
</p>

## Development Setup
Describe how to install all development dependencies and how to run an automated test-suite of some kind:

```sh
# Install dependencies
npm install

# Run tests
npm test

# Start development server
npm start
```

## Release History
* 0.1.0
    * Initial release of Kaam Kaji List
    * Basic task management functionality
    * Dark theme implementation
