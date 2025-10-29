<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aye Mon San - CV</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    background-color: #f4f7f8;
    color: #333;
  }

  /* Header */
  .header {
    background-color: #e6d6f7; /* light purple */
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 20px 40px;
    border-bottom: 1px solid #d0b3f2;
    flex-wrap: wrap;
  }
  .header-profile {
    display: flex;
    align-items: center;
  }
  .header-profile img {
    width: 120px;
    height: 120px;
    border-radius: 12px;
    object-fit: cover;
    margin-left: 20px;
  }
  .header-info {
    text-align: right;
  }
  .header-info h1 {
    margin: 0;
    font-size: 26px;
    color: #4b0082;
  }
  .header-info h2 {
    margin: 5px 0 0 0;
    font-size: 16px;
    font-weight: 400;
    color: #333;
  }

  /* Main container */
  .container {
    max-width: 900px;
    margin: 30px auto;
    display: flex;
    gap: 30px;
    padding: 0 20px;
    flex-wrap: wrap;
  }

  /* Sidebar */
  .sidebar {
    flex: 1 1 30%;
    background-color: #f0f0f0;
    border-radius: 12px;
    padding: 20px;
    min-width: 250px;
    box-sizing: border-box;
  }
  .sidebar h3 {
    color: #6a0dad;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
  }
  .sidebar h3::before {
    content: "💡";
    margin-right: 8px;
  }
  .sidebar ul {
    list-style: none;
    padding-left: 0;
  }
  .sidebar li {
    margin-bottom: 8px;
  }

  /* Main content */
  .main {
    flex: 1 1 65%;
    min-width: 300px;
  }
  .main h3 {
    color: #6a0dad;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
  }
  .main h3::before {
    content: "📌";
    margin-right: 8px;
  }
  .main .section {
    margin-bottom: 25px;
  }
  .main ul {
    list-style: disc;
    padding-left: 20px;
  }

  /* Individual icons for sections */
  .main h3.summary::before { content: "🧭"; }
  .main h3.education::before { content: "🎓"; }
  .main h3.work::before { content: "💼"; }
  .main h3.volunteer::before { content: "🌱"; }
  .main h3.certifications::before { content: "🏅"; }
  .main h3.personal::before { content: "👤"; }
  .main h3.online::before { content: "🔗"; }

  .sidebar h3.skills::before { content: "🛠"; }
  .sidebar h3.languages::before { content: "🌍"; }
  .sidebar h3.contact::before { content: "📬"; }

  a {
    color: #6a0dad;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .header {
      justify-content: center;
      text-align: center;
    }
    .header-info {
      text-align: center;
    }
    .header-profile {
      flex-direction: column-reverse;
      align-items: center;
    }
    .header-profile img {
      margin-left: 0;
      margin-top: 10px;
    }
    .container {
      flex-direction: column;
    }
    .sidebar, .main {
      flex: 1 1 100%;
    }
  }
</style>
</head>
<body>

<!-- Header -->
<div class="header">
  <div class="header-profile">
    <div class="header-info">
      <h1>Aye Mon San</h1>
      <h2>English Instructor</h2>
      <p>Payap University, International College</p>
      <p>Chiang Mai, Thailand</p>
    </div>
    <img src="amscvphoto.jpg" alt="Aye Mon San Photo">
  </div>
</div>

<!-- Body -->
<div class="container">
  <!-- Sidebar -->
  <div class="sidebar">
    <h3 class="contact">Contact</h3>
    <ul>
      <li>📧 <a href="mailto:miayemonsan34@gmail.com">miayemonsan34@gmail.com</a></li>
      <li>📞 092-396-9849</li>
    </ul>

    <h3 class="languages">Languages</h3>
    <ul>
      <li>Mon — Native</li>
      <li>Burmese — Fluent</li>
      <li>English — Proficient</li>
      <li>Thai — Intermediate</li>
    </ul>

    <h3 class="skills">Skills</h3>
    <ul>
      <li>Communication & Presentation</li>
      <li>Teamwork & Leadership</li>
      <li>Active Listening</li>
      <li>Adaptability</li>
      <li>Classroom Management</li>
      <li>Cross-cultural Understanding</li>
    </ul>
  </div>

  <!-- Main Content -->
  <div class="main">
    <div class="section">
      <h3 class="summary">Professional Summary</h3>
      <p>Motivated and passionate English Communication student with strong interest in teaching, intercultural communication, and lifelong learning. Experienced in volunteer teaching and community education projects. Dedicated to fostering inclusive and engaging learning environments that encourage students to develop linguistic and cultural competence.</p>
    </div>

    <div class="section">
      <h3 class="education">Education</h3>
      <ul>
        <li>B.A. English Communication Arts — Payap University (2024 – Present)</li>
        <li>Associate Degree — Mon National College (2021 – 2024)</li>
        <li>B.A. English — Hpa-An Distant University (2018 – 2019)</li>
      </ul>
    </div>

    <div class="section">
      <h3 class="work">Work Experience</h3>
      <ul>
        <li>Freelance English Tutor (Online) — Sep 2024 – Jul 2025  
        Provided one-on-one and group English lessons to learners from diverse backgrounds.</li>
        <li>Accountant — Nay La Kabar Co., Ltd (Nov 2018 – Jan 2019)</li>
        <li>Volunteer Teacher — Chiang Rai Kindergarten (Painting Project) (Jan 2025)</li>
      </ul>
    </div>

    <div class="section">
      <h3 class="volunteer">Volunteer Experience</h3>
      <ul>
        <li>English Teaching Assistant — Hpa-An Distant University (2018)</li>
        <li>Teacher — Mon Primary School (2020–2021)</li>
        <li>Teacher — Dhamma School (2019–2020)</li>
        <li>Teacher — Mon Literature Program (2016–2018)</li>
        <li>Online English Sharing Lessons — Ongoing</li>
      </ul>
    </div>

    <div class="section">
      <h3 class="certifications">Certifications & Training</h3>
      <ul>
        <li>Business Knowledge Sharing Workshop (2024)</li>
        <li>Career Planning and Job Search (2018)</li>
        <li>Mon Intensive English Program (2018)</li>
        <li>General English Elementary Level (2017)</li>
        <li>High School Certificate (2017)</li>
      </ul>
    </div>

    <div class="section">
      <h3 class="personal">Personal Information</h3>
      <ul>
        <li>Date of Birth: 30 September 1998</li>
        <li>Gender: Male</li>
        <li>Nationality: Myanmar</li>
        <li>Marital Status: Single</li>
        <li>Height / Weight: 164 cm / 52 kg</li>
      </ul>
    </div>

    <div class="section">
      <h3 class="online">Online Presence</h3>
      <ul>
        <li><a href="mailto:miayemonsan34@gmail.com">Email</a></li>
        <li><a href="https://github.com/yourusername" target="_blank">GitHub</a></li>
        <li>LinkedIn — (Add if available)</li>
      </ul>
    </div>
  </div>
</div>

</body>
</html>
