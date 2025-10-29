<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aye Mon San - Resume</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
    body {
        font-family: 'Poppins', sans-serif;
        background: #f5f7fa;
        margin: 0;
        color: #333;
    }

    .resume-container {
        max-width: 1000px;
        background: #fff;
        margin: 30px auto;
        border-radius: 12px;
        box-shadow: 0 0 15px rgba(0,0,0,0.1);
        overflow: hidden;
    }

    /* ---------- Header ---------- */
    .header {
        background: #2F4F4F;
        color: #fff;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 25px;
    }

    .header-info {
        max-width: 70%;
    }

    .header-info h1 {
        margin: 0;
        font-size: 36px;
        font-weight: 700;
    }

    .header-info p {
        margin: 5px 0;
        font-size: 18px;
    }

    .profile-photo {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        object-fit: cover;
        border: 4px solid #fff;
        box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    /* ---------- Content ---------- */
    .content {
        display: grid;
        grid-template-columns: 35% 65%;
    }

    .left, .right {
        padding: 25px;
    }

    .section-title {
        font-size: 20px;
        font-weight: 600;
        padding-bottom: 5px;
        margin-bottom: 12px;
        border-bottom: 3px solid #000000;
    }

    ul {
        margin: 0;
        padding-left: 18px;
    }

    p, li {
        font-size: 14px;
        line-height: 1.6rem;
    }

    .info-block p {
        margin: 6px 0;
    }

    /* ---------- Mobile Responsive ---------- */
    @media(max-width: 768px) {
        .content {
            grid-template-columns: 1fr;
        }
        .header {
            flex-direction: column;
            text-align: center;
        }
        .header-info {
            max-width: 100%;
        }
        .profile-photo {
            margin-top: 20px;
        }
    }
</style>
</head>

<body>

<div class="resume-container">

    <!-- Header -->
    <div class="header">
        <div class="header-info">
            <h1>Aye Mon San</h1>
            <p>Aspiring English Instructor</p>
            <p>📍 Chiang Mai, Thailand</p>
            <p>📞 0923969849 | 📧 miayemonsan34@gmail.com</p>
        </div>
        <img src="amscvphoto.jpg" alt="Profile Photo" class="profile-photo">
    </div>

    <div class="content">

        <!-- Left Column -->
        <div class="left">

            <div class="section-title">Personal Info</div>
            <p>Gender : Male</p>
            <p>DOB : 30 Sep 1998</p>
            <p>Nationality : Myanmar</p>
            <p>Marital Status : Single</p>
            <p>Height/Weight : 164 cm / 52 kg</p>

            <div class="section-title">Languages</div>
            <p>Burmese</p>
            <p>English</p>
            <p>Mon (Native)</p>
            <p>Thai</p>

            <div class="section-title">Skills</div>
            <p>• Organized</p>
            <p>• Active Listening</p>
            <p>• Interpersonal Communication</p>
            <p>• Adaptability</p>
            <p>• Cultural Awareness</p>

        </div>

        <!-- Right Column -->
        <div class="right">

            <div class="section-title">About Me</div>
            <p>I am a dedicated and passionate individual with a strong commitment to becoming an English Instructor. I aim to create supportive learning environments where students feel confident and motivated to achieve their goals through creative and interactive lessons.</p>

            <div class="section-title">Education</div>
            <ul>
                <li><strong>Payap University</strong> — Bachelor of English Communication Arts (2024 - Ongoing)</li>
                <li><strong>Mon National College</strong> — Associate Degree (2021 - 2024)</li>
                <li><strong>Hpa-An Distant University</strong> — Bachelor of English (2018 - 2019)</li>
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
                <li>English Teaching Assistant — Hpa-An Distant University (Sep - Oct 2018)</li>
                <li>Teaching in Mon Primary School (Sep 2020 - Apr 2021)</li>
                <li>Teaching in Dhamma School (Jun 2019 - Aug 2020)</li>
                <li>Teaching Mon Literature in the Village (2016 - 2018)</li>
                <li>Sharing English Lessons Online (Ongoing)</li>
            </ul>

            <div class="section-title">Certifications</div>
            <ul>
                <li>Workshop of Business Knowledge Sharing (2024)</li>
                <li>Mon Intensive English Program (2018)</li>
                <li>Career Planning and Job Search (2018)</li>
                <li>General English Elementary Level (2017)</li>
            </ul>

        </div>
    </div>
</div>

</body>
</html>
