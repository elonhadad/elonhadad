<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dark Mode Switch</title>
    <style>
        /* עיצוב רגיל */
        .container {
            background-color: #ffffff; /* רקע לבן */
            color: #000000; /* צבע טקסט שחור */
        }
        /* עיצוב למצב חושך */
        @media (prefers-color-scheme: dark) {
            .container {
                background-color: #222222; /* רקע כהה */
                color: #ffffff; /* צבע טקסט לבן */
            }
            .github-icon {
                content: url("https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg");
            }
            .linkedin-icon {
                content: url("https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg");
            }
        }
    </style>
</head>
<body>
    <div class="container">
        Hi 👋 My name is Elon Hadad Computer science student Now in the third year of the degree.
        * 🌍  I'm based in Qiryat Shmona, Israel
        * ✉️  You can contact me at <a href="mailto:elonhadad@gmail.com">elonhadad@gmail.com</a>
        * 🧠  currently i'm learning Angular, JS, Typescript, C#
        <h3>Skills</h3>
        <p>Skills content here...</p>
        <h3>Socials</h3>
        <p>
            <a href="https://www.github.com/elonhadad" target="_blank" rel="noreferrer" class="github-icon">
                <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" />
            </a>
            <a href="https://www.linkedin.com/in/elonhadad" target="_blank" rel="noreferrer" class="linkedin-icon">
                <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" />
            </a>
        </p>
        <h3>Top Repositories</h3>
        <p>Top repositories content here...</p>
    </div>
</body>
</html>
