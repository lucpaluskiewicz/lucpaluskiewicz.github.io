<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Container for the layout */
        .container {
            display: flex;
            height: 100vh;
        }

        /* Fixed left column for contact and main information */
        .sidebar {
            width: 250px;
            background-color: #f4f4f4;
            padding: 20px;
            position: fixed;
            top: 0;
            bottom: 0;
        }

        /* Right column for scrollable content */
        .main-content {
            margin-left: 250px;
            padding: 20px;
            overflow-y: auto;
            flex-grow: 1;
        }

        /* Add styles for headers and links */
        h1, h2, h3 {
            color: #333;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Responsive adjustments */
        @media screen and (max-width: 768px) {
            .sidebar {
                width: 100%;
                position: relative;
                height: auto;
            }

            .main-content {
                margin-left: 0;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Left Column (Sidebar) -->
        <div class="sidebar">
            <h1>Your Name</h1>
            <p><strong>Email:</strong> your.email@example.com</p>
            <p><strong>Phone:</strong> +123 456 7890</p>
            <p><strong>LinkedIn:</strong> <a href="#">linkedin.com/in/yourprofile</a></p>
            <p><strong>GitHub:</strong> <a href="#">github.com/yourprofile</a></p>
        </div>

        <!-- Right Column (Main Content) -->
        <div class="main-content">
            <h2>Latest Research Publications</h2>
            <ul>
                <li><strong>Title of Paper 1</strong><br/>Journal Name, Year, Authors</li>
                <li><strong>Title of Paper 2</strong><br/>Journal Name, Year, Authors</li>
                <li><strong>Title of Paper 3</strong><br/>Journal Name, Year, Authors</li>
            </ul>

            <h2>Collaborations</h2>
            <ul>
                <li><strong>Research Group 1</strong><br/>Description of the collaboration</li>
                <li><strong>Research Group 2</strong><br/>Description of the collaboration</li>
                <li><strong>Research Group 3</strong><br/>Description of the collaboration</li>
            </ul>
        </div>
    </div>

</body>
</html>
