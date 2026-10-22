1. Starter Code Files

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Development Practice</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="card">
        <h1>Environment Setup Complete!</h1>
        <p>This project is running locally via VS Code Live Server.</p>
        <button id="demoBtn">Test Script</button>
        <p id="statusMsg"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>


style.css

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f0f2f5;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

.card {
    background: #ffffff;
    padding: 2.5rem;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
    max-width: 400px;
}

h1 {
    color: #1a73e8;
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

button {
    background-color: #1a73e8;
    color: white;
    border: none;
    padding: 0.6rem 1.2rem;
    font-size: 1rem;
    border-radius: 6px;
    cursor: pointer;
    transition: background 0.2s ease-in-out;
}

button:hover {
    background-color: #1557b0;
}

#statusMsg {
    margin-top: 1rem;
    font-weight: bold;
    color: #2e7d32;
}


script.js

console.log("Development environment loaded successfully!");

document.getElementById('demoBtn').addEventListener('click', () => {
    const statusMsg = document.getElementById('statusMsg');
    statusMsg.textContent = "JavaScript execution confirmed!";
});


2. Terminal Output Verification

$ node -v
v20.11.1

$ npm -v
10.2.4


3. Required Screenshot Placeholders for Submission

To complete your final submission, capture and attach these three specific screenshots:

Screenshot 1 — VS Code Workspace:

Shows VS Code open with the web-development-practice folder.

File explorer sidebar showing index.html, style.css, and script.js.

Extensions sidebar showing Live Server and Prettier installed.

Screenshot 2 — Terminal Verification:

Shows VS Code integrated terminal (Ctrl + ~).

Displays the execution of node -v and npm -v returning version numbers.

Screenshot 3 — Running Web Page:

Browser displaying http://127.0.0.1:5500/index.html launched via Live Server.