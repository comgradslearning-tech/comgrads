# comgrads
ComGrads Skill Center
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Comgrads Skills Center</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      line-height: 1.6;
      background: #fff;
      color: #333;
    }
    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(135deg, #FF6B35, #FF8E53);
      color: white;
    }
    header h1 {
      font-family: 'Montserrat', sans-serif;
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    header a {
      background: #fff;
      color: #FF6B35;
      padding: 12px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    header a:hover {
      background: #E85D25;
      color: #fff;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
      text-align: center;
    }
    section h2 {
      font-family: 'Montserrat', sans-serif;
      color: #E85D25;
      margin-bottom: 20px;
    }
    .courses {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .course-card {
      border: 1px solid #eee;
      border-radius: 12px;
      padding: 20px;
      transition: 0.3s;
    }
    .course-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    }
    .course-card h3 {
      font-family: 'Montserrat', sans-serif;
      color: #FF6B35;
      margin: 10px 0;
    }
    .course-card p {
      font-size: 0.95rem;
      margin-bottom: 15px;
    }
    .course-card a {
      background: #FF6B35;
      color: #fff;
      padding: 8px 16px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 0.9rem;
      transition: 0.3s;
    }
    .course-card a:hover {
      background: #E85D25;
    }
    footer {
      background: #FF6B35;
      color: white;
      text-align: center;
      padding: 15px;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Comgrads Skills Center</h1>
    <p>English Communication & Skill Development in Nashik</p>
    <a href="#courses">Explore Courses</a>
  </header>

  <section>
    <h2>About Us</h2>
    <p>At <strong>Comgrads Skills Center</strong>, we help learners build confidence in English speaking for academics, careers, and everyday life. Our method is simple: learn by practice — through role plays, group discussions, and interactive sessions.</p>
  </section>

  <section id="courses">
    <h2>Our Courses</h2>
    <div class="courses">
      <div class="course-card">
        <h3>💼 Business Communication Mastery</h3>
        <p>Excel at workplace communication: emails, meetings, and presentations.</p>
        <a href="#">Enroll Now</a>
      </div>
      <div class="course-card">
        <h3>📚 Academic Writing Excellence</h3>
        <p>Master research papers, citations, and academic vocabulary with precision.</p>
        <a href="#">Enroll Now</a>
      </div>
      <div class="course-card">
        <h3>🗣️ Conversational English Fluency</h3>
        <p>Build confidence in daily communication, pronunciation, and natural expression.</p>
        <a href="#">Enroll Now</a>
      </div>
    </div>
  </section>

  <section>
    <h2>Contact Us</h2>
    <p>📍 Nashik, Maharashtra<br>
    📞 +91 98765 43210<br>
    📧 info@comgrads.com</p>
    <p><a href="https://forms.gle/" target="_blank" style="background:#FF6B35; color:#fff; padding:10px 20px; border-radius:6px; text-decoration:none;">Send Enquiry</a></p>
  </section>

  <footer>
    © 2025 Comgrads Skills Center | All Rights Reserved
  </footer>

</body>
</html>
