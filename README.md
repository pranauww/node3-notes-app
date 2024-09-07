# Notes Application

## Overview
This **Notes Application** is a simple command-line tool built using **Node.js**. It allows you to add, remove, list, and read notes directly from the terminal. The app leverages the **Yargs** library for argument parsing and **Chalk** for colored console output.

## Features
- **Add Notes**: Create new notes by specifying a title and body.
- **Remove Notes**: Delete notes by title.
- **List Notes**: View a list of all notes with their titles.
- **Read Notes**: Read the content of a specific note by providing its title.

## Prerequisites
Ensure you have **Node.js** installed (version 12 or above).

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/notes-app.git
   cd notes-app
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

## Usage
This application is designed to be run from the command line. Below are the available commands:

### Add a Note
To add a note with a title and body:
```bash
node app.js add --title="Your Note Title" --body="Your Note Body"
```

### Remove a Note
To remove a note by its title:
```bash
node app.js remove --title="Your Note Title"
```

### List All Notes
To list all your notes:
```bash
node app.js list
```

### Read a Note
To read a specific note by its title:
```bash
node app.js read --title="Your Note Title"
```

## Commands
- **add**: Adds a new note.
- **remove**: Removes a note by title.
- **list**: Lists all saved notes.
- **read**: Reads the content of a note by title.

### Example Commands
1. Add a note:
   ```bash
   node app.js add --title="Shopping List" --body="Buy milk and eggs"
   ```

2. Remove a note:
   ```bash
   node app.js remove --title="Shopping List"
   ```

3. List all notes:
   ```bash
   node app.js list
   ```

4. Read a note:
   ```bash
   node app.js read --title="Shopping List"
   ```

## Dependencies
- **chalk**: For colorizing console output.
- **yargs**: For command-line argument parsing.
- **fs**: For reading and writing notes to the file system.
