
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Diwali</title>
    <link rel="stylesheet" href="diwalicode homepage.css">
</head>
<body>
    <div class="container">
        <h1>Best Wishes</h1>
        <p>Enter your name to receive a Diwali greeting:</p>
        <form id="nameForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            <button type="submit"><a class="submit" href="happy diwali.html">Submit</a></button>
        </form>
        <p id="greeting" class="hidden">Happy Diwali, <span id="Dinesh"></span>!</p>
    </div>
</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Sacramento&display=swap');

body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Use full height for the page */
    margin: 0; /* Remove default margin */
    background-color: #87CEEB;
    font-family: Arial, sans-serif;
}

.container {
    text-align: center;
    background-color: #ea8dce;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    filter: drop-shadow(1px 1px 20px rgb(244, 243, 244));
    width: 90%; /* Set width to 90% of screen */
    max-width: 500px; /* Set max width for larger screens */
    margin: 20px;
}

h1 {
    font-size: 2.5em;
    color: white;
    margin-bottom: 10px;
    font-family: 'Sacramento', cursive;
    text-shadow: 2px 2px 4px rgb(34, 33, 34);
}

p {
    font-size: 1.2em;
    color: #333;
}

form {
    margin-top: 25px;
}

input[type="text"] {
    padding: 12px;
    width: 100%; /* Make input field responsive */
    margin-bottom: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1em;
}

button {
    padding: 10px 20px;
    background-color: #32CD32;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1.1em;
    width: 100%; /* Full-width button */
}

button:hover {
    background-color: #228B22;
}

.hidden {
    display: none;
}

#greeting {
    margin-top: 15px;
    font-size: 1.5em;
    color: #8B0000;
}

.submit {
    text-decoration: none;
    color: white;
}

/* Media Queries for Responsiveness */
@media (max-width: 768px) {
    h1 {
        font-size: 2em; /* Smaller title on smaller screens */
    }

    p {
        font-size: 1em;
    }

    .container {
        padding: 10px; /* Less padding for smaller screens */
    }

    input[type="text"], button {
        font-size: 1em; /* Adjust font size */
    }

    button {
        padding: 10px;
    }
}

@media (max-width: 480px) {
    h1 {
        font-size: 1.8em; /* Even smaller title on very small screens */
    }

    .container {
        padding: 8px; /* Even less padding */
    }

    p {
        font-size: 0.9em;
    }

    input[type="text"] {
        padding: 8px;
    }

    button {
        padding: 8px;
    }

    #greeting {
        font-size: 1.3em;
    }
}
