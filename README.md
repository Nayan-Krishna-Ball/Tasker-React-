Tasker – React Task Management App

Tasker is a simple and intuitive task-management application built with React. It allows users to create, search, manage, and display tasks efficiently through a clean, component-based architecture.

🚀 Features

Add new tasks using a modal form

Search tasks dynamically

Perform task actions (mark complete, delete, etc.)

View a structured task list

Responsive UI with header, hero section, and footer

“No Task Found” message for empty results

Modular & maintainable component structure

Project Structure
Main App Structure

<App /> renders the main layout of the application:

<Header /> – Top navigation/header section

<Hero /> – Intro or banner section

<TaskBoard /> – Core task-management interface

<Footer /> – Page footer

TaskBoard Components

The <TaskBoard /> is composed of:

<AddTaskModal /> – Popup/modal to add a new task

<SearchTask /> – Component for searching/filtering tasks

<TaskAction /> – Buttons or controls for managing tasks

<TaskList /> – Displays all tasks

<NoTaskFound /> – Shown when no tasks match search criteria

🏗️ Tech Stack

React.js

JavaScript (ES6+)

CSS / Tailwind / Styled Components

Vite /

src/
├── components/
│ ├── Header/
│ ├── Hero/
│ ├── Footer/
│ └── TaskBoard/
│ ├── AddTaskModal/
│ ├── SearchTask/
│ ├── TaskAction/
│ ├── TaskList/
│ └── NoTaskFound/
├── App.jsc
├── main.js
└── styles/
