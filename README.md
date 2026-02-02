<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bibek Das | AI & Software Engineer</title>

  <!-- Font Awesome -->
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
  />

  <style>
    :root {
      --primary: #4f46e5;
      --secondary: #111827;
      --text: #374151;
      --muted: #6b7280;
      --bg: #f9fafb;
      --card: #ffffff;
      --border: #e5e7eb;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: var(--primary);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .container {
      max-width: 1100px;
      margin: 2rem auto;
      padding: 1.5rem;
    }

    header {
      background: var(--card);
      border: 1px solid var(--border);
      padding: 2rem;
      border-radius: 12px;
      margin-bottom: 2rem;
    }

    header h1 {
      color: var(--secondary);
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
    }

    header p {
      color: var(--muted);
      margin-bottom: 1rem;
    }

    .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      font-size: 0.95rem;
    }

    .contact span {
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    main {
      display: grid;
      grid-template-columns: 1fr 2.2fr;
      gap: 2rem;
    }

    section {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }

    section h2 {
      font-size: 1.2rem;
      color: var(--secondary);
      margin-bottom: 1rem;
      border-bottom: 2px solid var(--border);
      padding-bottom: 0.4rem;
    }

    ul {
      list-style: none;
    }

    ul li {
      margin-bottom: 0.6rem;
    }

    .tag {
      display: inline-block;
      background: #eef2ff;
      color: var(--primary);
      padding: 0.2rem 0.6rem;
      border-radius: 6px;
      font-size: 0.8rem;
      margin-right: 0.3rem;
      margin-top: 0.3rem;
    }

    .project {
      margin-bottom: 1.5rem;
    }

    .project h3 {
      font-size: 1rem;
      color: var(--secondary);
    }

    .project span {
      font-size: 0.85rem;
      color: var(--muted);
    }

    .project ul {
      margin-top: 0.5rem;
      padding-left: 1rem;
    }

    .project ul li {
      list-style: disc;
      margin-bottom: 0.4rem;
    }

    .links a {
      display: inline-block;
      margin-right: 1rem;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      margin-top: 2rem;
      color: var(--muted);
      font-size: 0.85rem;
    }

    @media (max-width: 900px) {
      main {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <!-- HEADER -->
    <header>
      <h1>Bibek Das</h1>
      <p>Aspiring AI / LLM Engineer & Software Engineer</p>

      <div class="contact">
        <span><i class="fa-solid fa-location-dot"></i> Agarpara, West Bengal</span>
        <span><i class="fa-solid fa-phone"></i> +91 9051776463</span>
        <span>
          <i class="fa-solid fa-envelope"></i>
          <a href="mailto:bibekdas1055@gmail.com">bibekdas1055@gmail.com</a>
        </span>
        <span>
          <i class="fa-brands fa-linkedin"></i>
          <a href="https://linkedin.com/in/bibek-das" target="_blank">LinkedIn</a>
        </span>
        <span>
          <i class="fa-brands fa-github"></i>
          <a href="https://github.com/Be-bibek" target="_blank">GitHub</a>
        </span>
      </div>
    </header>

    <!-- MAIN CONTENT -->
    <main>
      <!-- LEFT COLUMN -->
      <div>
        <section>
          <h2>About Me</h2>
          <p>
            I am an aspiring AI / LLM Engineer and Software Engineer with hands-on
            experience in Python, deep learning, backend systems, and cloud-native
            development. I enjoy building real-world AI-driven applications that
            combine machine learning, system-level engineering, and scalable
            infrastructure.
          </p>
        </section>

        <section>
          <h2>Core Skills</h2>
          <ul>
            <li><strong>Languages:</strong> Python, Java, JavaScript, Dart, SQL</li>
            <li><strong>AI / ML:</strong> Deep Learning, Computer Vision, RAG, Model Serving</li>
            <li><strong>Backend:</strong> Flask, FastAPI, REST APIs</li>
            <li><strong>Cloud:</strong> Oracle Cloud Infrastructure (OCI), Docker, CI/CD</li>
            <li><strong>Systems:</strong> Linux, Embedded Linux, Raspberry Pi</li>
          </ul>
        </section>

        <section>
          <h2>Certifications</h2>
          <ul>
            <li>
              AI & Machine Learning — Google for Developers (AICTE EduSkills)
              <br />
              <a href="#" target="_blank">[ Add Certificate Link ]</a>
            </li>
            <li>
              NVIDIA Deep Learning Institute — Getting Started with Deep Learning
              <br />
              <a href="#" target="_blank">[ Add Credential URL ]</a>
            </li>
            <li>
              Oracle Cloud Infrastructure — Data Science Professional
              <br />
              <a href="#" target="_blank">[ Add Oracle Credential ]</a>
            </li>
            <li>
              Oracle AI Vector Search Professional
              <br />
              <a href="#" target="_blank">[ Add Credential URL ]</a>
            </li>
          </ul>
        </section>
      </div>

      <!-- RIGHT COLUMN -->
      <div>
        <section>
          <h2>Projects</h2>

          <div class="project">
            <h3>AI-Powered Autonomous Rover</h3>
            <span>Linux • Python • Flask • Flutter • Computer Vision</span>
            <ul>
              <li>
                Designed and developed a Linux-based autonomous rover with
                real-time decision-making, obstacle avoidance, and intelligent navigation.
              </li>
              <li>
                Built a Flask backend for rover control, sensor fusion, camera
                streams, and AI inference pipelines.
              </li>
              <li>
                Developed a Flutter mobile app for live monitoring, control, and
                interaction with onboard systems.
              </li>
              <li>
                Integrated on-device AI inference for object detection and
                environment awareness.
              </li>
            </ul>
            <div class="links">
              <a href="#" target="_blank">GitHub Repo</a>
              <a href="#" target="_blank">Project README</a>
            </div>
          </div>

          <div class="project">
            <h3>AI-Powered Healthcare Management System</h3>
            <span>Flutter • Firebase • AI • Razorpay</span>
            <ul>
              <li>
                Built a cross-platform healthcare application with EHR management,
                appointment booking, and telemedicine features.
              </li>
              <li>
                Integrated AI models for medical report analysis and patient
                summary generation.
              </li>
              <li>
                Implemented secure Razorpay payment gateway for online consultations.
              </li>
            </ul>
            <div class="links">
              <a href="#" target="_blank">GitHub Repo</a>
              <a href="#" target="_blank">Project README</a>
            </div>
          </div>
        </section>

        <section>
          <h2>Education</h2>
          <p>
            <strong>B.Tech in Electronics and Communication Engineering</strong><br />
            Guru Nanak Institute of Technology, Kolkata<br />
            <span>2023 – 2027 (Ongoing)</span>
          </p>
        </section>

        <section>
          <h2>Resume</h2>
          <p>
            <a href="#" target="_blank">Download PDF Resume</a>
          </p>
        </section>
      </div>
    </main>

    <footer>
      © 2026 Bibek Das • Built with HTML5 & CSS
    </footer>
  </div>
</body>
</html>

![](https://github-readme-stats.vercel.app/api?username=Be-bibek&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=Be-bibek&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Be-bibek&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
