
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Repository Link</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f6f9;
            color: #222;
            margin: 0;
            padding: 30px;
            line-height: 1.6;
        }

        .container {
            max-width: 850px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
        }

        h1, h2 {
            color: #2563eb;
        }

        pre {
            background: #1e293b;
            color: white;
            padding: 15px;
            border-radius: 8px;
            overflow-x: auto;
        }

        .note {
            background: #eff6ff;
            padding: 15px;
            border-left: 4px solid #2563eb;
        }

        a {
            color: #2563eb;
            overflow-wrap: anywhere;
        }
    </style>
</head>

<body>
    <div class="container">

        <h1>GitHub Repository Link</h1>

        <p>
            GitHub is a platform used to store, manage, and share
            code online. Git helps track changes in a project.
        </p>

        <h2>1. Create a GitHub Repository</h2>

        <ol>
            <li>Open <a href="https://github.com/" target="_blank">GitHub</a>.</li>
            <li>Click the New repository button.</li>
            <li>Name the repository
                <strong>html-css-assignments</strong>.</li>
            <li>Leave the repository empty without a README.</li>
            <li>Click Create repository.</li>
        </ol>

        <h2>2. Push Your Local Project</h2>

        <p>Open the terminal inside your project folder and run:</p>

        <pre><code>git remote add origin https://github.com/YOUR-USERNAME/html-css-assignments.git
git branch -M main
git push -u origin main</code></pre>

        <p>
            Replace <strong>YOUR-USERNAME</strong> with your actual
            GitHub username.
        </p>

        <h2>3. Verify Your Repository</h2>

        <p>
            Refresh your GitHub repository page and check that
            your files and commit history are visible.
        </p>

        <h2>4. Host the Website for Free (Optional)</h2>

        <ol>
            <li>Open your repository on GitHub.</li>
            <li>Go to Settings → Pages.</li>
            <li>Select the main branch and root folder.</li>
            <li>Click Save.</li>
        </ol>

        <p>Your website link will look like this:</p>

        <pre><code>https://YOUR-USERNAME.github.io/html-css-assignments/</code></pre>

        <h2>5. Submission</h2>

        <p><strong>https://github.com/manishgautam2005/html-css-assignments:</strong></p>

        <p>
            <a href="https://github.com/" target="_blank">
                https://github.com/YOUR-USERNAME/html-css-assignments
            </a>
        </p>

        <div class="note">
            <strong>Important:</strong> The submission link will work
            only after you create the repository and push your files.
        </div>

    </div>
</body>
</html>
