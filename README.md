<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aye Mon San - Resume</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Poppins', sans-serif;
    background: #f9f9f9;
    margin: 0;
    padding: 0;
    color: #333;
  }

  .resume-container {
    max-width: 1000px;
    background: #fff;
    margin: 25px auto;
    border-radius: 12px;
    box-shadow: 0 0 15px rgba(0,0,0,0.1);
    display: flex;
    flex-wrap: wrap;
    overflow: hidden;
  }

  /* Sidebar */
  .left {
    flex: 1 1 35%;
    min-width: 280px;
    background: #6a0dad;
    color: #fff;
    padding: 60px 25px 40px 25px;
    position: relative;
  }

  /* Profile */
  .profile {
    text-align: center;
    margin-bottom: 25px;
  }
  .profile img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #fff;
    margin-bottom: 10px;
  }
  .profile h1 {
    font-size: 22px;
    margin: 0;
    font-weight: 600;
  }
  .profile h2 {
    font-size: 16px;
    font-weight: 400;
    margin: 4px 0 0 0;
  }

  .section-title {
    font-size: 18px;
    font-weight: 600;
    margin-top: 20px;
    margin-bottom: 8px;
    border-bottom: 2px solid #d3a4ff;
    padding-bottom: 4px;
  }

  p, li {
    font-size: 14px;
    line-height: 1.5rem;
    margin: 4px 0;
  }
  ul {
    padding-left: 18px;
    margin: 0;
  }

  a {
    color: #fff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }

  /* Main content */
  .right {
    flex: 1 1 65%;
    min-width: 300px;
    padding: 60px 35px 40px 35px;
    background: #fff;
    color: #333;
  }
  .right .section-title {
    border-bottom: 2px solid #6a0dad;
  }
  .right p, .right li {
    color: #333;
  }
  .right a {
    color: #6a0dad;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .resume-container {
      flex-direction: column;
    }
    .left, .right {
      flex: 1 1 100%;
      min-width: auto;
      padding: 40px 20px;
    }
    .profile img {
      width: 100px;
      height: 100px;
    }
  }
</style>
</head>
<body>

<div class="resume-container">

  <!-- Left Sidebar -->
  <div class="left">
    <div class="profile">
      <img src="amscvphoto.jpg" alt="Aye Mon San Photo">
      <h1>Aye Mon San</h1>
      <h2>English Instructor</h2>
    </div>

    <div class="section-title">Contact Info</div>
    <p>📍 Chiang Mai, Thailand</p>
    <p>📞 0923969849</p>
    <p>📧 <a href="mailto:miayemonsan34@gmail.com">miayemonsan34@gmail.com</a></p>

    <div class="section-title">Personal Info</div>
    <p>Gender: Male</p>
    <p>DOB: 30 Sep 1998</p>
    <p>Nationality: Myanmar</p>
    <p>Marital Status: Single</p>
    <p>Height/Weight: 164 cm / 52 kg</p>

    <div class="section-title">Languages</div>
    <p>Mon (Native)</p>
    <p>Burmese</p>
    <p>English</p>
    <p>Thai</p>

    <div class="section-title">Skills</div>
    <p>• Organized</p>
    <p>• Active Listening</p>
    <p>• Interpersonal Communication</p>
    <p>• Adaptability</p>
    <p>• Cultural Awareness</p>
  </div>

  <!-- Right Content -->
  <div class="right">
    <div class="section-title">About Me</div>
    <p>I am a dedicated and passionate individual with a strong commitment to becoming an English Instructor. I aim to create supportive learning environments where students feel confident and motivated.</p>

    <div class="section-title">Education</div>
    <ul>
      <li>Payap University — Bachelor of English Communication Arts (2024 - Ongoing)</li>
      <li>Mon National College — Associate Degree (2021 - 2024)</li>
      <li>Hpa-An Distant University — Bachelor of English (2018 - 2019)</li>
      <li>High School Graduate</li>
    </ul>

    <div class="section-title">Experience</div>
    <ul>
      <li>Freelance Online English Teaching (Sep 2024 - Jul 2025)</li>
      <li>Painting at Chiang Rai Kindergarten (Jan 2025)</li>
      <li>Accountant — Nay La Kabar Co., Ltd (Nov 2018 - Jan 2019)</li>
    </ul>

    <div class="section-title">Volunteer</div>
    <ul>
      <li>English Teaching Assistant at Hpa-An Distant University (Sep - Oct 2018)</li>
      <li>Teaching in Mon Primary School (Sep 2020 - Apr 2021)</li>
      <li>Teaching in Dhamma School (Jun 2019 - Aug 2020)</li>
      <li>Teaching Mon Literature in the Village (2016 - 2018)</li>
      <li>Sharing English Lessons Online (Ongoing)</li>
    </ul>

    <div class="section-title">Certifications</div>
    <ul>
      <li>Workshop of Business Knowledge Sharing (2024)</li>
      <li>High School (2016-2017)</li>
      <li>Mon Intensive English Program (2018)</li>
      <li>Career Planning and Job Search (2018)</li>
      <li>General English Elementary Level (2017)</li>
    </ul>
  </div>
</div>

</body>
</html>
