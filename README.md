<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kyle Dixon</title>
  <meta name="description" content="Kyle Dixon – student and aspiring public interest professional." />

  <!-- Simple, GitHub Pages–friendly styling -->
  <style>
    :root {
      --bg: #ffffff;
      --text: #111827;
      --muted: #4b5563;
      --accent: #1f2937;
      --link: #2563eb;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      color: var(--text);
      background: var(--bg);
      line-height: 1.6;
    }

    header {
      border-bottom: 1px solid #e5e7eb;
      padding: 2.5rem 1.5rem;
    }

    main {
      max-width: 900px;
      margin: 0 auto;
      padding: 2rem 1.5rem 4rem;
    }

    h1 {
      font-size: 2.5rem;
      margin: 0 0 0.5rem 0;
      letter-spacing: -0.02em;
    }

    h2 {
      font-size: 1.5rem;
      margin-top: 3rem;
      margin-bottom: 0.75rem;
      border-bottom: 1px solid #e5e7eb;
      padding-bottom: 0.25rem;
    }

    p {
      margin: 0.5rem 0 1rem 0;
    }

    .subtitle {
      color: var(--muted);
      font-size: 1.1rem;
      max-width: 700px;
    }

    .links a {
      margin-right: 1.25rem;
      text-decoration: none;
      color: var(--link);
      font-weight: 500;
    }

    .links a:hover {
      text-decoration: underline;
    }

    ul {
      padding-left: 1.25rem;
    }

    footer {
      border-top: 1px solid #e5e7eb;
      padding: 1.5rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.9rem;
    }

    /* Optional: subtle print styling for PDF export */
    @media print {
      header, footer { border: none; }
      a { color: black; text-decoration: none; }
    }
  </style>
</head>
<body>
  <header>
    <main>
      <h1>Kyle Dixon</h1>
      <p class="subtitle">
        Student with interests in law, public service, and civic institutions. 
        Focused on understanding how legal and governmental systems can better serve the public.
      </p>
      <div class="links">
        <!-- Update links as needed -->
        <a href="https://www.linkedin.com/in/kyle-winn-dixon/" target="_blank" rel="noopener">LinkedIn</a>
        <a href="Kyle_Dixon_Resume.pdf">Resume (PDF)</a>
        <a href="mailto:your.email@example.com">Email</a>
      </div>
    </main>
  </header>

  <main>
    <section id="about">
      <h2>About</h2>
      <p>
        I am currently a student with a strong interest in law, public defense, and public service. 
        My academic and professional experiences are centered on understanding legal systems, 
        civic responsibility, and the role of institutions in advancing justice and accountability.
      </p>
      <p>
        I am particularly interested in opportunities that combine rigorous legal analysis with 
        real-world impact, including public interest law, government service, and policy-oriented work.
      </p>
    </section>

    <section id="interests">
      <h2>Interests</h2>
      <ul>
        <li>Public interest and public defense</li>
        <li>Criminal justice and legal reform</li>
        <li>Government and civic institutions</li>
        <li>Law, policy, and democratic accountability</li>
        <li>Research, writing, and analysis</li>
      </ul>
    </section>

    <section id="experience">
      <h2>Experience</h2>
      <p>
        <!-- Replace this paragraph with a concise summary pulled from your resume -->
        I have experience in academic research, student organizations, and professional settings 
        related to law and public service. My work emphasizes careful analysis, clear communication, 
        and a commitment to ethical and community-focused outcomes.
      </p>
      <p>
        For a detailed overview of my background, please see my resume.
      </p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p>
        <!-- Edit as appropriate -->
        Stanford University (current)
      </p>
      <p>
        Coursework and interests include political science, law, public policy, and related fields.
      </p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>
        The best way to reach me is by email. I am open to conversations about research, public service 
        opportunities, and collaborative projects.
      </p>
      <p>
        <strong>Email:</strong> your.email@example.com
      </p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Kyle Dixon
  </footer>

  <script>
    // Automatically update the year in the footer
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
