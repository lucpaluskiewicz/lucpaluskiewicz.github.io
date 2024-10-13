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
            width: 350px;  /* Increased width */
            background-color: #f4f4f4;
            padding: 20px;
            position: fixed;
            top: 0;
            bottom: 0;
        }

        /* Right column for scrollable content */
        .main-content {
            margin-left: 350px;  /* Adjust margin for the larger sidebar */
            padding: 20px;
            overflow-y: auto;
            flex-grow: 1;
        }

        /* Add styles for headers and links */
        h1, h2, h3 {
            color: #333;
        }

        a {
            color: #8B0000; /* Dark brick color */
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Style for logos in the sidebar */
        .sidebar img {
            width: 20px;
            height: 20px;
            vertical-align: middle;
            margin-right: 10px;
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
            <p>
                <img src="linkedin-logo.png" alt="LinkedIn">
                <a href="#">LinkedIn</a>
            </p>
            <p>
                <img src="github-logo.png" alt="GitHub">
                <a href="#">GitHub</a>
            </p>
            <!-- Add more logos for other platforms -->
        </div>

        <!-- Right Column (Main Content) -->
        <div class="main-content">
            <!-- Links at the top for navigation -->
            <nav>
                <a href="#publications">Research Publications</a> | 
                <a href="#collaborations">Collaborations</a>
            </nav>
            <hr/>

            <h2 id="publications">Latest Research Publications</h2>
            <ul>
                <li><strong>Title of Paper 1</strong><br/>Journal Name, Year, Authors</li>
                <li><strong>Title of Paper 2</strong><br/>Journal Name, Year, Authors</li>
                <li><strong>Title of Paper 3</strong><br/>Journal Name, Year, Authors</li>
            </ul>

            <h2 id="collaborations">Collaborations</h2>
            <ul>
                <li><strong>Research Group 1</strong><br/>Description of the collaboration</li>
                <li><strong>Research Group 2</strong><br/>Description of the collaboration</li>
                <li><strong>Research Group 3</strong><br/>Description of the collaboration</li>
            </ul>
        </div>
    </div>

</body>
</html>
