
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML & CSS Assignments - Git Repository</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 30px;
            background-color: #f4f6f9;
            color: #222;
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 12px;
        }

        h1, h2 {
            color: #1d4ed8;
        }

        pre {
            background: #1e293b;
            color: #f8fafc;
            padding: 18px;
            border-radius: 8px;
            overflow-x: auto;
        }

        code {
            font-family: Consolas, monospace;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: left;
        }

        th {
            background-color: #1d4ed8;
            color: white;
        }

        tr:nth-child(even) {
            background-color: #f1f5f9;
        }

        .note {
            background: #eff6ff;
            padding: 15px;
            border-left: 4px solid #1d4ed8;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <div class="container">

        <h1>HTML & CSS Assignments</h1>
        <p>
            This repository contains HTML and CSS assignments,
            Git setup instructions, and project development history.
        </p>

        <h2>1. Git Identity Setup</h2>
        <p>Configure your Git username and email:</p>

        <pre><code>git config --global user.name "Your Name"
git config --global user.email "you@example.com"</code></pre>

        <h2>2. Create the Repository</h2>

        <pre><code>mkdir html-css-assignments
cd html-css-assignments
git init
git branch -M main</code></pre>

        <h2>3. Make at Least Three Meaningful Commits</h2>

        <h3>Commit 1: Add README</h3>
        <pre><code>echo "# HTML & CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README with project overview"</code></pre>

        <h3>Commit 2: Add Assignments 1–5</h3>
        <pre><code>cp -r /path/to/this/folder/assignments .
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup & git assignments (1-5)"</code></pre>

        <h3>Commit 3: Add HTML Assignments 6–10</h3>
        <pre><code>git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments (6-10)"</code></pre>

        <h2>4. Check Commit History</h2>
        <pre><code>git log --oneline</code></pre>

        <div class="note">
            <strong>Note:</strong> Replace the sample Git username,
            email, and folder path with your actual details.
            The assignment files must exist before you can add and commit them.
        </div>

        <h2>5. Suggested Git Commit History</h2>

        <table>
            <thead>
                <tr>
                    <th>Commit</th>
                    <th>Commit Message</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>1</td><td>docs: add README</td></tr>
                <tr><td>2</td><td>docs: setup & git assignments (1-5)</td></tr>
                <tr><td>3</td><td>feat: HTML basics (6-10)</td></tr>
                <tr><td>4</td><td>feat: links, images, lists (11-15)</td></tr>
                <tr><td>5</td><td>feat: forms, tables, metadata (16-20)</td></tr>
                <tr><td>6</td><td>style: CSS fundamentals (21-25)</td></tr>
                <tr><td>7</td><td>style: box model & positioning (26-30)</td></tr>
                <tr><td>8</td><td>feat: flexbox layouts (31-35)</td></tr>
                <tr><td>9</td><td>feat: grid layouts (36-40)</td></tr>
                <tr><td>10</td><td>feat: responsive landing page (41-45)</td></tr>
            </tbody>
        </table>

        <h2>6. Good Commit Message Rules</h2>
        <ul>
            <li>Use clear, action-oriented messages.</li>
            <li>Use prefixes like feat, fix, docs, and style.</li>
            <li>Keep each commit focused on one logical change.</li>
        </ul>

        <p><strong>Conclusion:</strong> A meaningful Git history
        shows your project progress and helps demonstrate your work.</p>

    </div>
</body>
</html>
