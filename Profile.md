<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khemika Chan-Ngam Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #EAF8E6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #A9D5A5;
            color: #2C5F2D;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 90%;
            width: 800px;
            margin: 20px auto;
            background-color: #FFFFFF;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            padding: 20px;
        }
        h1, h2 {
            color: #2C5F2D;
        }
        .profile {
            text-align: center;
        }
        .profile img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
            border: 4px solid #A9D5A5;
        }
        .profile p {
            color: #4F7942;
            font-size: 1em;
            margin: 5px 0;
        }
        a {
            color: #2C5F2D;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #A9D5A5;
            color: #FFFFFF;
            margin-top: 20px;
        }
        .project-section {
            margin-top: 20px;
        }
        .project-section p {
            margin: 5px 0;
        }

        /* Media Queries for Responsive Design */
        @media (min-width: 768px) {
            .profile img {
                width: 150px;
                height: 150px;
            }
            .profile p {
                font-size: 1.1em;
            }
        }

        @media (max-width: 768px) {
            header {
                padding: 15px;
            }
            .container {
                padding: 15px;
            }
            .profile img {
                width: 80px;
                height: 80px;
            }
            .profile p {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Portfolio of Kemikha Chan-Ngam</h1>
    </header>
    <div class="container">
        <section class="profile">
            <img src="img/IMG_0400.jpeg" alt="Kemikha's Profile Picture">
            <p><strong>Name:</strong> Kemikha Chan-Ngam</p>
            <p><strong>Age:</strong> 20 years old</p>
            <p><strong>Education:</strong> Computer Science Major, Kasetsart University, Sriracha Campus</p>
            <p><strong>Interests:</strong> Reading books, learning Salesforce, playing badminton, exercising</p>
            <p><strong>Google Drive:</strong> <a href="https://drive.google.com/drive/folders/1kykv4aPr5izAWq7ornx6RPqOwE1AqjXR" target="_blank">View My Project Files</a></p>
            <p><strong>Trailhead:</strong> <a href="https://www.salesforce.com/trailblazer/loe4c1rkfbg65vqscd" target="_blank">View My Trailhead Profile</a></p>
        </section>
      <section class="project-section">
            <h2>Projects</h2>
          <p><strong>Geographical Indication:</strong> <a href="https://public.tableau.com/app/profile/kemikha.chan.ngam/viz/GI_Ex4/GI?publish=yes" target="_blank">View Dashboard</a></p>
            <p><strong>Marvel Dashboard:</strong> <a href="https://public.tableau.com/app/profile/kemikha.chan.ngam/viz/Dashboard_Mavel/Dashboard" target="_blank">View Dashboard</a></p>
            <p><strong>Marvel Story:</strong> <a href="https://public.tableau.com/app/profile/kemikha.chan.ngam/viz/Story_Mavel/Story" target="_blank">View Story</a></p>
            <h3>Project Description:</h3>
            <ul>
                <li>Compare Revenue: Analyze global revenue for movies across different film studios.</li>
                <li>Profit/Loss Analysis: Evaluate production budgets versus revenue to calculate profitability.</li>
                <li>Relevance to Marvel: Identify which studio movies belong to the Marvel Universe.</li>
            </ul>
        </section>
    </div>
    <footer>
        <p>&copy; 096-371-5424 | Email: <a href="mailto:kemikha.c@gmail.com">kemikha.c@gmail.com</a></p>
    </footer>
</body>
</html>

