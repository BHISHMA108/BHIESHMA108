<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional Developer Profile</title>
    <style>
        body {
            font-family: 'Righteous', sans-serif;
            background: linear-gradient(45deg, #111, #333);
            color: white;
            margin: 0;
            overflow: hidden;
        }
        h1, h3 {
            text-align: center;
        }
        .container {
            text-align: center;
            margin-top: 50px;
        }
        .badges {
            margin-top: 20px;
        }
        .badges img {
            margin: 0 10px;
        }
        .stats {
            margin-top: 50px;
        }
        .languages-tools img {
            margin: 5px;
        }
        #background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            background: url('/mnt/data/A_professional_developer_profile_page_with_an_inte.png') no-repeat center center/cover;
            animation: gradientMove 5s infinite alternate;
        }
        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            100% { background-position: 100% 50%; }
        }
    </style>
</head>
<body>

<div id="background"></div>

<h1>Hi There! 👋 I'm Pedro Muniz!</h1>
<h3>A passionate software developer from Canada 🇨🇦</h3>

<div class="container">
    <div class="badges">
        <a href="mailto:pedro.sales.muniz@gmail.com"><img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail" alt="Gmail"></a>
        <a href="https://linkedin.com/in/pedro-sales-muniz" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"></a>
        <a href="https://salesp07.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-orange?style=for-the-badge&logo=portfolio" alt="Portfolio"></a>
    </div>

    <div class="languages-tools">
        <h2>⚒️ Languages-Frameworks-Tools ⚒️</h2>
        <img src="https://skillicons.dev/icons?i=react,nodejs,python,mongodb,firebase,java" alt="Tools and Languages">
    </div>

    <div class="stats">
        <h2>⚡ Stats ⚡</h2>
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=salesp07&theme=dark" alt="GitHub Stats">
        <img src="https://github-readme-stats.vercel.app/api?username=salesp07&show_icons=true&theme=dark" alt="GitHub Contributions">
    </div>
</div>

</body>
</html>
