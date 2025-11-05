# notes-app
A simple notes management app built with React to practice state management, component communication, and modular architecture.  Users can create, view, and delete notes with categorized priorities (High, Medium, Low). The app demonstrates the use of props, state, conditional rendering, and component decomposition in React.


Features

📝 Add new notes with title, category, priority, and description.

🗂️ Display all notes dynamically using reusable components.

🧹 Delete notes with confirmation prompt.

🎨 Priority-based border color (High → red, Medium → orange, Low → green).

🧩 Components separated for clarity and scalability:

App → main state holder

NoteForm → input form

NoteList → renders a list of notes

Note → single note card

SelectInput & TextAreaInput → reusable form elements

Tech Stack

React.js

JavaScript (ES6+)

Tailwind CSS for styling

Vite
