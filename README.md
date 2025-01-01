<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luc Paluskiewicz Personal Website</title>
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
            width: 400px;  /* Increased width */
            background-color: #f4f4f4;
            padding: 20px;
            position: fixed;
            top: 0;
            bottom: 0;
        }

        /* Right column for scrollable content */
        .main-content {
            margin-left: 400px;  /* Adjust margin for the larger sidebar */
            padding: 20px;
            overflow-y: auto;
            flex-grow: 1;
        }

        /* General styles for headers and links */
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

        /* Styling the email in brick color */
        .email {
            color: #8B0000;  /* Dark brick color for email */
        }

        /* Style for logos in the sidebar */
        .sidebar img {
            width: 20px;
            height: 20px;
            vertical-align: middle;
            margin-right: 10px;
        }

        /* Space for image */
        .profile-image {
            margin-top: 20px;
            width: 150px;  /* Example size for the profile image */
            height: 150px;
            border-radius: 50%;
            display: block;
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
            <h1>Luc Paluskiewicz</h1>

            <!-- Placeholder for your image -->
            <img src="your-image.jpg" alt="Your Photo" class="profile-image">

            <p><strong>Email:</strong> <span class="email">luc.paluskiewicz[at]psemail.eu</span></p>
            <p><strong></strong> <span class="email">luc.paluskiewicz[at]college-de-france.fr</span></p>

            <p><strong>Adress:</strong> Collège de France, 3 rue d'Ulm 75005 Paris.</p>

        </div>

        <!-- Right Column (Main Content) -->
        <div class="main-content">
            <!-- Navigation links to other pages -->
            <nav>
                <a href="https://lucpaluskiewicz.github.io/">Home</a> |
                <a href="https://lucpaluskiewicz.github.io/research" target="_blank">Research</a> |
                <a href="https://lucpaluskiewicz.github.io/cv" target="_blank">CV</a>
            </nav>
            <hr/>

            <!-- General description -->
            <p>
                I am Luc Paluskiewicz, PhD candidate in Economics at the Paris School of Economics and the Collège de France. 
            </p>

        </div>
    </div>

</body>
</html>
