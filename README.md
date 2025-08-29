# Ex01 Portfolio
## Date: 29.08.2025.

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume - Nithya shree.B</title>
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <div class="resume">
        <!-- Page 1 -->
        <section class="page">
            <header>
                <div class="header-content">
                    <div class="profile-image">
                        <img src="WhatsApp Image 2024-12-07 at 12.36.17_199d9aa7.jpg" alt="Profile Photo">
                    </div>
                    <div class="text-content">
                        <h1>NITHYA SHREE B</h1>
                        <p>B.TECH IT | 3nd Year Student</p>
                        <p>Roll No: 212223220071</p>
                        <p>Email: nithubalu2006@gmail.com | Phone: +91 9043857529</p>
                        <p>GitHub: github.com/Balunithu</p>
                    </div>
                </div>
            </header>
            <hr>
            <section>
                <h2>Skills</h2>
                <ul>
                    <li>C Programming, Python (Basics)</li>
                    <li>Networking Fundamentals</li>
                    <li>Cybersecurity Basics</li>
                    <li>Problem Solving</li>
                </ul>
            </section>
            <section>
                <h2>Experience</h2>
                <h3>Student Coordinator | Saveetha Engineering College</h3>
                <p>2023 - Present</p>
                <ul>
                    <li>Assisted in exam coordination and technical tasks.</li>
                    <li>Performed vulnerability checking and version monitoring.</li>
                </ul>
                <h3>Self-Learning Projects</h3>
                <p>2023 - Present</p>
                <ul>
                    <li>Learning cybersecurity with practical exercises.</li>
                    <li>Created basic network scanning and testing scripts.</li>
                </ul>
            </section>
        </section>

        <!-- Page 2 -->
        <section class="page">
            <section>
                <h2>Projects</h2>
                <h3>Zero-Day Threat Prediction AI (In Progress)</h3>
                <p>Building an AI system to predict and detect new threats early.</p>
                <h3>Network Security Automation (Planned)</h3>
                <p>Creating RPA bots for security testing using UiPath and Python.</p>
            </section>
            <section>
                <h2>Education</h2>
                <h3>Bachelor of Technology - Information Technology</h3>
                <p>Saveetha Engineering College | 2023 - 2027</p>
            </section>
        </section>
    </div>
    <style>
        img{
           height: 150px;
            width: 160px;
            border: solid 10px;
        }
    </style>
</body>
</html>

## CSS
```
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #cd63f4; /* start with lavender */
    color: #000000; /* black text */
    animation: blinkBackground 2s infinite; /* background blinking */
}

@keyframes blinkBackground {
    0%, 100% {
        background-color: #c7efde; /* lavender */
    }
    50% {
        background-color: #96dfe9; /* black */
    }
}

.resume {
    width: 800px;
    margin: auto;
    background: linear-gradient(135deg, #37263b, #e6e6fa); /* white to lavender inside */
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2); /* soft black shadow */
}

.page {
    border: 1px solid #000000; /* black border */
    padding: 20px;
    margin-bottom: 20px;
    background-color: #c2a7ee; /* white page background */
    border-radius: 10px;
}

h1 {
    margin-bottom: 5px;
    font-size: 32px;
    color: #000000; /* black heading */
}

hr {
    border: 1px solid #000000; /* black horizontal line */
}

ul {
    list-style-type: square;
}

.header-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
    background: #ffffff; /* white header background */
    border-radius: 10px;
    box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.5); /* black shadow */
}

.profile-image img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid #000000; /* black border around photo */
}

.text-content {
    flex: 1;
    text-align: center;
}

h2 {
    color: #000000; /* black sub-headings */
}
```
## OUTPUT

![Screenshot 2025-04-30 102923](https://github.com/user-attachments/assets/acb6ed2f-7e0c-4e5e-a331-0fe29e779860)

![Screenshot 2025-04-30 102939](https://github.com/user-attachments/assets/64f0ce83-e0f7-4811-a661-054b99b570aa)
