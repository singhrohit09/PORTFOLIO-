<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rohit Singh | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f4f7fb;
    color:#333;
}

/* ---------- HEADER ---------- */
header{
    background:url("https://camo.githubusercontent.com/c8154fa9ed572d021bcb93598c636b257c5aa22d5f10bcc290ff7cb0afd7f207/68747470733a2f2f692e696d6775722e636f6d2f344153616679302e706e67") center/cover no-repeat;
    color:#fff;
    padding:90px 20px 70px;
    text-align:center;
    position:relative;
}

/* Dark overlay so text becomes visible */
header::before{
    content:"";
    position:absolute;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.55);
    z-index:0;
}

header *{
    position:relative;
    z-index:1;
}

header img{
    width:220px;
    border-radius:15px;
    border:4px solid #fff;
    margin-bottom:20px;
}

/* NAME FIXED VISIBILITY */
header h1{
    font-size:3rem;
    letter-spacing:2px;
    color:#ffffff;
    text-shadow:0 4px 12px rgba(0,0,0,0.8);
    margin-bottom:10px;
}

.header-badge{
    display:inline-block;
    background:rgba(255,255,255,0.15);
    padding:10px 18px;
    border-radius:25px;
    font-size:1rem;
    backdrop-filter:blur(6px);
}

/* ---------- CONTAINER ---------- */
.container{
    max-width:1100px;
    margin:auto;
    padding:50px 20px;
}

/* ---------- CARD ---------- */
.card{
    background:#fff;
    border-radius:18px;
    padding:35px 40px;
    margin-bottom:35px;
    box-shadow:0 15px 35px rgba(0,0,0,0.08);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-6px);
    box-shadow:0 25px 45px rgba(0,0,0,0.12);
}

/* ---------- HEADINGS ---------- */
h2{
    color:#667eea;
    margin-bottom:20px;
    text-align:center;
    position:relative;
}

h2::after{
    content:'';
    width:70px;
    height:4px;
    background:#764ba2;
    display:block;
    margin:10px auto 0;
    border-radius:5px;
}

/* ---------- TEXT ---------- */
p, .education-item, ul{
    line-height:1.8;
    text-align:left;
}

/* ---------- EDUCATION ---------- */
.education-item{
    margin-bottom:30px;
}

.education-item img{
    width:250px;
    border-radius:15px;
    margin-top:15px;
    transition:0.4s;
    display:block;
    margin-left:auto;
    margin-right:auto;
}

.education-item img:hover{
    transform:scale(1.05);
}

/* ---------- SKILLS ---------- */
.skills{
    text-align:center;
}

.skills span{
    display:inline-block;
    background:linear-gradient(135deg,#667eea,#764ba2);
    color:#fff;
    padding:10px 18px;
    border-radius:25px;
    margin:8px;
    font-size:0.9rem;
}

/* ---------- PROJECTS ---------- */
.project-img{
    display:block;
    margin:20px auto 0;
    width:260px;
    border-radius:15px;
    transition:0.4s;
}

.project-img:hover{
    transform:scale(1.05);
}

/* ---------- LINKS ---------- */
a{
    color:#764ba2;
    text-decoration:none;
    font-weight:600;
}

a:hover{
    text-decoration:underline;
}

/* ---------- LIST ---------- */
ul{
    list-style-position:inside;
    padding-left:0;
}

/* ---------- FOOTER ---------- */
footer{
    background:linear-gradient(120deg,#667eea,#764ba2);
    color:#fff;
    text-align:center;
    padding:25px;
    letter-spacing:1px;
}
</style>
</head>

<body>

<!-- HEADER -->
<header>
    <img src="https://lh3.google.com/u/0/p/AF1QipNoNkPhXCzwzUmyAFSqDsMlXkiGCxduF960uqod=w1032-h774" alt="Rohit Singh">
    <h1>ROHIT SINGH</h1>
    <div class="header-badge">ENTC Engineering Student | Passionate Tech Learner</div>
</header>

<div class="container">

<!-- ABOUT -->
<div class="card">
    <h2>About Me</h2>
    <p>
        I am a First Year Electronics and Telecommunication Engineering student with a strong interest in electronics, sensors, and emerging technologies. I am passionate about learning new skills, building technical projects, and exploring innovative ideas. Currently, I am developing my knowledge in Arduino, programming, and circuit design to build a strong foundation for my engineering career
    </p>
</div>


<!-- CAREER OBJECTIVE -->
<div class="card">
    <h2>Career Objective</h2>
    <p>
        To build a strong career in Electronics and Telecommunication Engineering by gaining practical knowledge, developing technical skills, and working on innovative projects. I aim to contribute to technological advancements while continuously learning emerging technologies and improving my problem-solving abilities.
    </p>
</div>

<!-- EDUCATION -->
<div class="card">
    <h2>Education</h2>

    <div class="education-item">
        <strong>B.Tech in Electronics and Telecommunication Engineering</strong><br>
        MIT Academy of Engineering, Pune
        <br>
        <a href="https://mitaoe.ac.in/img/campus7.jpg" target="_blank">
            <img src="https://mitaoe.ac.in/img/campus7.jpg" alt="MITAOE">
        </a>
    </div>

    <div class="education-item">
        <strong>12th Standard</strong><br>
        Pune International School
        <br>
        <a href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCHjsZqlBYwg7A4aXIbmez98lhtYS-34diXQ&s" target="_blank">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRCHjsZqlBYwg7A4aXIbmez98lhtYS-34diXQ&s" alt="12th">
        </a>
    </div>

    <div class="education-item">
        <strong>10th Standard</strong><br>
        Kendriya Vidyalaya No. 2, AFS Pune-32
        <br>
        <a href="https://cdnbbsr.s3waas.gov.in/s3kv04dab686b0ee76b5edf6fc317c51d6/uploads/2024/08/2024082816-1-1024x768.jpg" target="_blank">
            <img src="https://cdnbbsr.s3waas.gov.in/s3kv04dab686b0ee76b5edf6fc317c51d6/uploads/2024/08/2024082816-1-1024x768.jpg" alt="10th">
        </a>
    </div>
</div>

<!-- SKILLS -->
<div class="card skills">
    <h2>Technical Skills</h2>
    <span>HTML</span>
    <span>C Programming</span>
    <span>Python</span>
    <span>Basic Electronics</span>
</div>

<!-- PROJECTS -->
<div class="card">
    <h2>Projects</h2>

    <p><strong>Digital Menu Card</strong><br>
    A clean and responsive digital menu card designed using HTML.</p>

    🔗 <a href="https://github.com/singhrohit09/MENU-PROJECT/blob/main/index.html" target="_blank">Fixed Menu Project</a><br>
    🔗 <a href="https://github.com/singhrohit09/EDITABLE-MENU-CARD/blob/main/index.html" target="_blank">Editable Menu Project</a>

    <p style="margin-top:25px;"><strong>Traffic Light Signal System</strong><br>
    Electronic project to understand timing control and logic circuits.</p>

    <img class="project-img" src="https://techatronic.com/wp-content/uploads/2021/10/WhatsApp-Image-2021-10-23-at-12.26.13-AM-3-600x800.jpeg">
</div>

<!-- ACHIEVEMENTS -->
<div class="card">
    <h2>Achievements</h2>
    <ul>
        <li>Regional level Handball player (10th)</li>
        <li>First Prize – Basketball (10th class School Level)</li>
        <li>First Prize – Skit Competition(7th)</li>
        <li>Second Prize – Football(9th class School Level)</li>
    </ul>
</div>

<!-- CONTACT -->
<div class="card">
    <h2>Contact</h2>
    <p>Email: singhkrissh067@gmail.com</p>
    <p>Phone: 7798678479</p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/rohit-singh-9752a1397" target="_blank">View Profile</a></p>
    <p>GitHub: <a href="https://github.com/singhrohit09" target="_blank">View Profile</a></p>
</div>

</div>

<footer>
    © 2026 Rohit Singh | Personal Portfolio 🚀
</footer>

</body>
</html>
