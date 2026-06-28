# Pragati-Patil-07
Fake websites detection 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fake Website Detection</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🛡 Fake Website Detection</h1>
    <p>Check whether a website may be safe or suspicious.</p>
</header>

<div class="container">

    <div class="card">
        <h2>Enter Website URL</h2>

        <input
            type="text"
            id="url"
            placeholder="Example: https://example.com">

        <button onclick="checkWebsite()">
            Check Website
        </button>

        <div id="result"></div>
    </div>

    <div class="card">
        <h2>How It Works</h2>

        <ul>
            <li>✔ Checks if HTTPS is used.</li>
            <li>✔ Detects suspicious keywords.</li>
            <li>✔ Looks for IP address URLs.</li>
            <li>✔ Gives a basic safety result.</li>
        </ul>
    </div>

    <div class="card">
        <h2>Tips to Stay Safe</h2>

        <ul>
            <li>Never click unknown links.</li>
            <li>Always verify HTTPS.</li>
            <li>Check the domain name carefully.</li>
            <li>Avoid entering passwords on suspicious websites.</li>
        </ul>
    </div>

</div>

<footer>
    <p>Cyber Security Project | Fake Website Detection</p>
</footer>

<script src="script.js"></script>

</body>
</html>
