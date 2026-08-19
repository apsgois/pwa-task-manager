# PWA Task Manager

A lightweight **Progressive Web App (PWA)** for task management, built with HTML, CSS, and JavaScript.

The application implements CRUD operations with local data persistence using **IndexedDB** and offline capabilities through a **Service Worker**.

## 💡 Project Overview

This project explores the fundamental concepts behind Progressive Web Applications by implementing a simple task management system.

Users can create and manage tasks directly in the browser while the application stores data locally using IndexedDB.

The Service Worker provides resource caching, allowing the application to maintain basic functionality even when network access is unavailable.

## ✨ Features

* Create tasks
* View saved tasks
* Edit existing tasks
* Delete tasks
* Local data persistence
* Offline resource caching
* Progressive Web App configuration

## 🔄 CRUD Operations

The application implements the four fundamental CRUD operations:

* **Create** — add new tasks
* **Read** — retrieve and display saved tasks
* **Update** — edit existing tasks
* **Delete** — remove tasks

Task data is persisted locally using **IndexedDB**.

## 📱 Progressive Web App

The project includes the main components required for a basic PWA:

### Service Worker

The Service Worker caches application resources and handles network requests, providing basic offline support.

### Web App Manifest

The `manifest.json` file defines metadata used by browsers when the application is installed as a Progressive Web App.

### IndexedDB

IndexedDB is used as the client-side database for storing task information directly in the browser.

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Progressive Web Apps (PWA)
* IndexedDB
* Service Workers
* Web App Manifest

## 📂 Project Structure

```text
.
├── app.js
├── index.html
├── manifest.json
├── service-worker.js
├── styles.css
├── .gitignore
├── LICENSE
└── README.md
```

## 🏗️ Application Flow

```text
User
  │
  ▼
Web Interface
  │
  ▼
JavaScript Application
  │
  ├── CRUD Operations
  │
  ▼
IndexedDB
  │
  └── Local Task Storage

Service Worker
  │
  └── Resource Cache / Offline Support
```

## 💡 Concepts Explored

This project provided practical experience with:

* Progressive Web Applications
* Client-side data persistence
* IndexedDB
* Service Workers
* Offline-first concepts
* CRUD operations
* Browser APIs
* JavaScript DOM manipulation
* Web application architecture

## 🎓 Project Context

This project was developed as a practical exercise to explore Progressive Web Application concepts and browser-based data persistence.

It is maintained as part of my portfolio to document my experience with modern Web APIs, offline capabilities, and client-side application development.

## 📄 License

This project is licensed under the MIT License.
