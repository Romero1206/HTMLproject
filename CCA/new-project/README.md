# New Project

A project with a main page linking to three embedded content pages.

## Getting Started

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server using `npm start`.

## Project Structure

```
new-project
├── src
│   ├── index.html
│   ├── page1.html
│   ├── page2.html
│   ├── page3.html
│   ├── page4.html
│   └── styles.css
├── package.json
└── README.md
```

## Saving the Project to GitHub

1. Create a new repository on GitHub.
2. Initialize a local Git repository:
    ```sh
    git init
    ```
3. Add the remote repository:
    ```sh
    git remote add origin <your-repository-url>
    ```
4. Add all files to the repository:
    ```sh
    git add .
    ```
5. Commit the changes:
    ```sh
    git commit -m "Initial commit"
    ```
6. Push the changes to GitHub:
    ```sh
    git push -u origin main
    ```

## Deploying to GitHub Pages

1. Install the `gh-pages` package as a dev dependency:
    ```sh
    npm install gh-pages --save-dev
    ```
2. Add the following scripts to your `package.json`:
    ```json
    "scripts": {
        "predeploy": "npm run build",
        "deploy": "gh-pages -d src"
    }
    ```
3. Deploy the project:
    ```sh
    npm run deploy
    ```

## License

This project is licensed under the MIT License.
