# To-Do List App 📝 

A simple and elegant To-Do List application built with React, featuring task addition, completion toggle, and deletion functionality. This app allows you to manage your tasks easily, with an intuitive user interface and smooth interactions.


---


## 🖥️ Live Demo 

> Link to the live demo, if hosted (e.g., Vercel, Netlify).

---


## 📂 Project Structure 


```css
src/
├── components/
│   └── Main.js          # Main To-Do List component
└── App.js               # Main application file
```


---


## 📚 Features 
 
- **Add Tasks** : Enter a new task and add it to your to-do list.
 
- **Toggle Task Completion** : Mark tasks as complete or incomplete.
 
- **Delete Tasks** : Remove tasks from the list.
 
- **Keyboard Support** : Press "Enter" to add a new task quickly.


---


## 🛠️ Technologies Used 
 
- **React** : Frontend framework for building user interfaces.
 
- **Lucide React** : For clean, responsive icons.
 
- **Tailwind CSS** : Styling for a responsive and attractive UI.


---


## 🚀 Getting Started 

### Prerequisites 
 
- **Node.js**  (>=14.0)
 
- **NPM**  (or **Yarn** )

### Installation 
 
1. Clone this repository:

```bash
git clone https://github.com/yourusername/todo-list-app.git
```
 
2. Install dependencies:

```bash
cd todo-list-app
npm install
```
 
3. Start the development server:

```bash
npm start
```
The app should be running at `http://localhost:3000`.

---


## 📄 Code Explanation 
Main Component (`Main.js`) 
- **`useState` Hooks** : Tracks `todos` and the `newTodo` input.
 
- **`addTodo`** : Adds a new task if the input isn't empty.
 
- **`toggleTodo`** : Toggles the `completed` status of a task.
 
- **`deleteTodo`** : Removes a task from the list by its unique `id`.

### Input and Button 
 
- The input field captures task names and triggers `addTodo` on pressing "Enter" or clicking "Add."

### Task Display 

- Each task shows with a checkbox to toggle completion, the task text, and a delete icon.


---


## 🎨 Styling 
 
- **Tailwind CSS** : Styles the layout for responsiveness, with rounded corners, shadow effects, and utility classes.


---


## 🤝 Contributing 

Contributions, suggestions, and improvements are always welcome! Please fork the repository, create a branch, make your changes, and submit a pull request.
