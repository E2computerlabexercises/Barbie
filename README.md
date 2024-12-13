<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LAB EXERCISES</title>
  <style>
    /* General Styling */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f1c40f; /* Bright yellow theme */
      color: #2c3e50;
    }
    header {
      background-color: #2c3e50; /* Dark header background */
      color: #f39c12; /* Bright accent color */
      text-align: center;
      padding: 20px 0;
    }
    header h1, header h2 {
      margin: 0;
    }
    section {
      padding: 20px;
    }
    section h2 {
      color: #f39c12;
    }
    footer {
      text-align: center;
      background-color: #2c3e50;
      color: #f39c12;
      padding: 10px 0;
    }
    footer nav a {
      color: #f39c12;
      text-decoration: none;
      margin: 0 15px;
      font-size: 1.2em;
    }
    footer nav a:hover {
      text-decoration: underline;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }
    table, th, td {
      border: 1px solid #333;
    }
    th, td {
      padding: 10px;
      text-align: left;
    }
    iframe {
      display: block;
      margin: 20px auto;
      max-width: 100%;
    }
    form {
      margin: 20px 0;
    }
    form label {
      display: block;
      margin: 10px 0 5px;
    }
    form input, form select, form button {
      padding: 10px;
      width: 100%;
      max-width: 400px;
    }
    .blog-image {
      width: 100%;
      max-width: 600px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>LAB EXERCISES</h1>
    <h2>E2 - COMPUTER</h2>
    <p>Author: [Your Name]</p>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Home Section -->
    <section id="home">
      <h2>Hello!</h2>
      <p>My Webpage contains a blog about malware,virus,spam and anti-virus and an article about plagiarism</p>
    </section>
    <!-- Plagiarism Section -->
    <section id="plagiarism">
      <h2>Plagiarism Deterred Through Information, Not Threats</h2>
      <p>By David Nagel, 02/02/10</p>
      <p>
        Giving students a Web-based tutorial on plagiarism is more effective in deterring the behavior than threatening students with detection and punishment.
        The study "Rational Ignorance in Education: A Field Experiment in Student Plagiarism" found that incidents of plagiarism could be reduced by 65% through a 15-minute Web-based tutorial teaching what constitutes plagiarism and how to avoid it.
      </p>
      <p>
        Among the control group, 3.3% of papers were flagged for plagiarism, while the frequency for the Web tutorial group dropped to about 1.3%.
      </p>
      <p>
        Researchers concluded that improving student knowledge reduced plagiarism rather than the fear of detection or punishment.
      </p>
      <!-- Embedded Video -->
      <iframe width="560" height="315" src="https://www.youtube.com/embed/EraEV3aOMJc?si=pBxEywls6JFq2Efj" title="Plagiarism Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>
    <!-- Blog Section -->
    <section id="blog">
      <h2>Blog: Viruses, Malware, Spam, and Antiviruses</h2>
      <img src="https://www.csoonline.com/wp-content/uploads/2021/06/what-is-malware.jpg" alt="Malware Image" class="blog-image">
      <p>The digital world is filled with threats like viruses, malware, and spam that can compromise personal data and system integrity. Here's an overview:</p>
      <ul>
        <li><strong>Viruses:</strong> Malicious software that damages systems and steals data.</li>
        <li><strong>Malware:</strong> Harmful programs like viruses, worms, and ransomware.</li>
        <li><strong>Spam:</strong> Unsolicited emails that often spread malware or phishing links.</li>
      </ul>
      <p><strong>Antiviruses:</strong> Antivirus software is essential to detect and remove harmful programs from devices. Regular updates and caution while browsing can prevent infections.</p>
    </section>
    <!-- Forms Section -->
    <section id="form">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="gender">Gender:</label>
        <input type="radio" id="male" name="gender" value="male"> Male
        <input type="radio" id="female" name="gender" value="female"> Female
        <label for="hobbies">Favorite Colors:</label>
        <input type="checkbox" id="pink" name="hobbies" value="pink"> Pink
        <input type="checkbox" id="blue" name="hobbies" value="blue"> Blue
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <label for="country">Country:</label>
        <select id="country" name="country">
          <option value="philippines">Philippines</option>
          <option value="china">China</option>
          <option value="japan">Japan</option>
        </select>
        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <p></p>
    <nav>
      <a href="#home">Home</a>
      <a href="#plagiarism">Plagiarism</a>
      <a href="#blog">Blog</a>
      <a href="#form">Forms</a>
    </nav>
  </footer>
</body>
</html>
