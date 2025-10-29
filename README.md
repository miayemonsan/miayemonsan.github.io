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
    width: 100%;
    height: 130px;
    background: #6a0dad;
    position: relative;
  }

  /* Container */
  .container {
    max-width: 900px;
    margin: -60px auto 40px; /* profile overlaps header */
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 12px 25px rgba(0,0,0,0.1);
    display: flex;
    flex-wrap: wrap;
    overflow: hidden;
  }

  /* Sidebar */
  .sidebar {
    background: #7b1fa2;
    color: #fff;
    padding: 120px 25px 40px 25px; /* top padding for profile */
    flex: 1 1 35%;
    min-width: 280px;
    position: relative;
  }

  /* Profile */
  .profile {
    position: absolute;
    top: -60px;
    left: 25px;
    display: flex;
    align-items: center;
  }
  .profile img {
    width: 110px;
    height: 110px;
    border-radius: 50%;
    border: 4px solid #fff;
    object-fit: cover;
    margin-right: 15px;
    background: #fff;
  }
  .profile-info h1 {
    font-size: 22px;
    margin: 0;
    font-weight: 600;
  }
  .profile-info h2 {
    font-size: 16px;
    font-weight: 400;
    margin: 4px 0 0 0;
  }

  .sidebar hr {
    border: 0.5px solid #d3a4ff;
    margin: 20px 0;
  }
  .sidebar p, .sidebar li {
    font-size: 14px;
    line-height: 1.6;
  }
  .sidebar ul {
    list-style: none;
    padding-left: 0;
  }

  /* Main content */
  .main {
    flex: 1 1 65%;
    padding: 60px 35px 40px 35px;
    min-width: 300px;
  }
  .main h3 {
    color: #6a0dad;
    margin-bottom: 10px;
    font-size: 18px;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .main h3::before {
    content: '•';
    color: #d3a4ff;
    font-weight: bold;
    margin-right: 8px;
  }

  .section {
    margin-bottom: 30px;
  }
  .section ul {
    list-style: disc;
    padding-left: 20px;
  }
  .languages table {
    width: 100%;
    border-collapse: collapse;
  }
  .languages th, .languages td {
    text-align: left;
    padding: 5px 0;
  }
  .languages th {
    width: 40%;
  }

  a {
    color: #d3a4ff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
      margin-top: 0;
    }
    .sidebar, .main {
      flex: 1 1 100%;
      min-width: auto;
      padding-top: 80px;
    }
    .profile {
      position: relative;
      top: 0;
      left: 0;
      margin-bottom: 20px;
    }
  }
</style>
</head>
<body>

<!-- Header -->
<div class="header"></div>

<div class="container">
  <!-- Sidebar -->
  <div class="sidebar">
    <div class="profile">
      <img src="amscvphoto.jpg" alt="Aye Mon San Photo">
      <div class="profile-info">
        <h1>Aye Mon San</h1>
        <h2>English Instructor</h2>
      </div>
    </div>

    <p>📍 Chiang Mai, Thailand</p>
    <p>📧 <a href="mailto:miayemonsan34@gmail.com">miayemonsan34@gmail.com</a></p>
    <p>📞 092-396-9849</p>
    <hr>

    <div class="section">
      <h3>🌱 Volunteer Experience</h3>
      <ul>
        <li>English Teaching Assistant — Hpa-An Distant University (2018)</li>
        <li>Teacher — Mon Primary School (2020–2021)</li>
        <li>Teacher — Dhamma School (2019–2020)</li>
        <li>Teacher — Mon Literature Program (2016–2018)</li>
        <li>Online English Sharing Lessons — Ongoing</li>
      </ul>
    </div>

    <div class="section">
      <h3>🏅 Certifications & Training</h3>
      <ul>
        <li>Business Knowledge Sharing Workshop (2024)</li>
        <li>Career Planning and Job Search (2018)</li>
        <li>Mon Intensive English Program (2018)</li>
        <li>General English Elementary Level (2017)</li>
        <li>High School Certificate (2017)</li>
      </ul>
    </div>

    <div class="section languages">
      <h3>🌍 Languages</h3>
      <table>
        <tr><th>Mon</th><td>Native</td></tr>
        <tr><th>Burmese</th><td>Fluent</td></tr>
        <tr><th>English</th><td>Proficient</td></tr>
        <tr><th>Thai</th><td>Intermediate</td></tr>
      </table>
    </div>
  </div>

  <!-- Main -->
  <div class="main">
    <div class="section">
      <h3>🧭 Professional Summary</h3>
      <p>Motivated and passionate English Communication student with strong interest in teaching, intercultural communication, and lifelong learning. Experienced in volunteer teaching and community education projects. Dedicated to fostering inclusive and engaging learning environments that encourage students to develop linguistic and cultural competence.</p>
    </div>

    <div class="section">
      <h3>🎓 Education</h3>
      <ul>
        <li><b>Payap University</b> — B.A. in English Communication Arts (2024 – Present)</li>
        <li><b>Mon National College</b> — Associate Degree (2021 – 2024)</li>
        <li><b>Hpa-An Distant University</b> — B.A. in English (2018 – 2019)</li>
      </ul>
    </div>

    <div class="section">
      <h3>💼 Work Experience</h3>
      <ul>
        <li><b>Freelance English Tutor (Online)</b> (Sep 2024 – Jul 2025)<br>
        Provided one-on-one and group English lessons to learners from diverse backgrounds. Focused on improving conversation, grammar, and pronunciation through interactive sessions.</li>
        <li><b>Accountant — Nay La Kabar Co., Ltd</b> (Nov 2018 – Jan 2019)<br>
        Handled financial records and assisted in preparing daily reports. Developed attention to detail and organizational skills.</li>
        <li><b>Volunteer Teacher — Chiang Rai Kindergarten (Painting Project)</b> (Jan 2025)<br>
        Assisted in school improvement projects and English-related activities.</li>
      </ul>
    </div>

    <div class="section">
      <h3>💡 Key Skills</h3>
      <ul>
        <li>Excellent Communication & Presentation</li>
        <li>Teamwork & Leadership</li>
        <li>Active Listening</li>
        <li>Adaptability</li>
        <li>Classroom Management</li>
        <li>Cross-cultural Understanding</li>
      </ul>
    </div>

    <div class="section">
      <h3>👤 Personal Information</h3>
      <ul>
        <li>Date of Birth: 30 September 1998</li>
        <li>Gender: Male</li>
        <li>Nationality: Myanmar</li>
        <li>Marital Status: Single</li>
        <li>Height / Weight: 164 cm / 52 kg</li>
      </ul>
    </div>

    <div class="section">
      <h3>🔗 Online Presence</h3>
      <ul>
        <li><a href="mailto:miayemonsan34@gmail.com">Email</a></li>
        <li><a href="https://github.com/yourusername" target="_blank">GitHub</a></li>
        <li><a href="#">LinkedIn (Add if available)</a></li>
      </ul>
    </div>
  </div>
</div>

</body>
</html>
