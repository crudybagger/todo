# Todo List App
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

git, npm / yarn and Node.js installed

### Cloning the project

Execute these commands at a path to clone the project from GitHub

```
git clone https://github.com/crudybagger/todo.git  
cd todo
git submodule update --init
```

#### Note: The next step requires 2 separate terminal tabs.

### Installing

Installing NPM modules on both client and server folders

Execute these commands in seprate terminal tabs from the project directory

Tab 1:
```
cd client && npm install
```
Tab 2:
```
cd server && npm install
```

### Running the app

In the same terminal tabs, execute the following commands

Tab 1:
```
npm run dev
```

Tab 2:
```
npm run start
```

Access the web app at http://localhost:5173/ or alternatively follow the link in Tab 1.
