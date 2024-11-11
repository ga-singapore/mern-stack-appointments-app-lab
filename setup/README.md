# ![React Components Lab - Setup](./assets/hero.png)

# Setup

Open your Terminal application and navigate to your `~/code/ga/labs` directory:

```bash
cd ~/code/ga/labs
mkdir mern-stack-appointments-app-lab
```


## Setup Frontend

Navigate to `mern-stack-appointments-app-lab` and create a new Vite project for your React app:

```bash
cd mern-stack-appointments-app-lab
npm create vite@latest
```

You'll be prompted to choose a project name. Let's name it `frontend`. 

- Select a framework. Use the arrow keys to choose the `React` option and hit `Enter`.

- Select a variant. Again, use the arrow keys to choose `JavaScript` and hit `Enter`.

Navigate to your new project directory and install the necessary dependencies:

```bash
cd frontend
npm i
```

Open the project's folder in your code editor:

```bash
code .
```

### Clear `App.jsx`

Open the `App.jsx` file in the `src` directory and replace the contents of it with the following:

```jsx
// src/App.jsx

const App = () => {

  return (
    <h1>Hello world!</h1>
  );
}

export default App
```


### Running the development server

To start the development server and view our app in the browser, we'll use the following command: 

```bash
npm run dev
```

You should see that `Vite` is available on port number 5173: 

```plaintext
localhost:5173
```


## Setup Backend

Navigate to `~/code/ga/labs/mern-stack-appointments-app-lab` and create a directory called backend.

```bash
mkdir backend
```

Initialise the directory and install `express` and `nodemon`.

```bash
npm init -y
npm i express
npm i -D nodemon
```


## GitHub setup

To add this project to GitHub, initialise a Git repository:

```bash
git init
git add .
git commit -m "init commit"
```

Make a new repository on [GitHub](https://github.com/) named react-components-lab. 

Link your local project to your remote GitHub repo:

```bash
git remote add origin https://github.com/<github-username>/mern-stack-appointments-app-lab.git
git push origin main
```

> 🚨 Do not copy the above command. It will not work. Your GitHub username will replace `<github-username>` (including the `<` and `>`) in the URL above.
