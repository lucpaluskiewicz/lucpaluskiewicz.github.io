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
            padding: 70px 20px 20px 20px; /* Top padding to make room for fixed navbar */
            overflow-y: auto;
            flex-grow: 1;
        }

        /* Fixed top navigation links */
        .top-nav {
            position: fixed;
            top: 0;
            left: 350px;  /* Make sure it's aligned after the sidebar */
            right: 0;
            background-color: #fff;
            padding: 10px;
            border-bottom: 1px solid #ccc;
            z-index: 1000;  /* Ensure it stays above other content */
            text-align: right;  /* Align links to the right */
        }

        .top-nav a {
            color: #8B0000;  /* Dark brick color */
            text-decoration: none;
            margin-left: 15px;
            font-weight: bold;
        }

        .top-nav a:hover {
            text-decoration: underline;
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

            .top-nav {
                left: 0;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Left Column (Sidebar) -->
        <div class="sidebar">
            <h1>Luc Paluskiewicz </h1>
            <p><strong>Email:</strong> luc.paluskiewicz@psemail.eu </p>
            <p><strong> </strong> luc.paluskiewicz@college-de-france.fr </p>
            <p>
                <img src="linkedin-logo.png" alt="LinkedIn">
                <a href="#">LinkedIn</a>
            </p>
            <p>
                <img src="github-logo.png" alt="GitHub">
                <a href="#">GitHub</a>
            </p>
        </div>

        <!-- Top Navigation (Fixed Links) -->
        <div class="top-nav">
            <a href="https://lucpaluskiewicz.github.io/research" target="_blank">Research</a>
            <a href="https://lucpaluskiewicz.github.io/cv" target="_blank">CV</a>
        </div>

        <!-- Right Column (Main Content) -->
        <div class="main-content">
        General description. 
        
    </div>

</body>
</html>
