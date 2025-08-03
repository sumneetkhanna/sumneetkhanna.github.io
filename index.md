<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sumneet Khanna | Analytics Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdfdfd;
    }
    .hero {
      background: linear-gradient(to right, #00b4db, #0083b0);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    .hero img {
      border-radius: 50%;
      width: 150px;
      margin-bottom: 20px;
    }
    .project-card {
      transition: 0.3s;
    }
    .project-card:hover {
      transform: scale(1.02);
    }
    .footer {
      background-color: #f8f9fa;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Sumneet Khanna</a>
      <div class="collapse navbar-collapse justify-content-end">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="assets/resume/Sumneet_Khanna_Resume.pdf" target="_blank">Resume</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="hero">
    <div class="container">
      <img src="assets/img/profile.jpg" alt="Sumneet's Photo">
      <h1 class="fw-bold">Hi, I'm Sumneet 👋</h1>
      <p class="lead">Data Analyst | Dashboarding Expert | NLP Enthusiast</p>
      <p>Turning data into decisions with purpose and clarity.</p>
    </div>
  </section>

  <section class="container py-5" id="projects">
    <h2 class="text-center mb-4">✨ Featured Projects</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card project-card h-100">
          <div class="card-body">
            <h5 class="card-title">Complaint Theme Detection using NLP</h5>
            <p class="card-text">Automated pipeline to identify and tag themes in complaints using NLP.</p>
            <a href="projects/complaint-nlp.html" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card project-card h-100">
          <div class="card-body">
            <h5 class="card-title">Credit Risk Dashboard</h5>
            <p class="card-text">Interactive Tableau dashboard for monitoring credit performance and trends.</p>
            <a href="projects/credit-risk.html" class="btn btn-primary">View Project</a>
          </div>
        </div>
      </div>
      <div
