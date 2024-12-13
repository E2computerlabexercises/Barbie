
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
    <h1>SANTOS, ALDRIN</h1>
    <h2>II- INDIA</h2>
    <p>LAB EXERCISES</p>
  </header>

  <!-- Main Content -->
  <main>
    <!-- Home Section -->
    <section id="home">
  <img src="images (2).png" alt="hello image" width="500">
      <audio controls>
  <source src="Dreamy.mp3">
  Your browser does not support the audio element.
</audio>
      <p>My Webpage contains a blog about malware,virus,spam and anti-virus and an article about plagiarism</p>
    </section>
    <!-- Plagiarism Section -->
    <section id="plagiarism">
      <h2>Plagiarism Deterred Through Information, Not Threats</h2>
      <p>By David Nagel, 02/02/10</p>
      <p>
        Giving students a Web-based tutorial on plagiarism is more effective in deterring the behavior than threatening students with detection and punishment. That's according to the results of an experiment conducted by professors at the University of Michigan and Swarthmore College and published as a working paper by the National Bureau of Economic Research.
      </p>
      <p>
        The study, "Rational Ignorance in Education: A Field Experiment in Student Plagiarism," found that incidents of plagiarism could be reduced by as much as 65 percent when students participated in a "15-minute Web-based tutorial that [taught them] what constitutes plagiarism and how to avoid it," according to information released by the University of Michigan. The experiment was conducted by Brian Jacob, Walter H. Annenberg Professor of Education Policy in the University of Michigan Gerald R. Ford School of Public Policy, and Thomas Dee, associate professor of economics and director of the public policy program in Swarthmore College's Department of Economics.
The experiment, which took place back in fall 2007, involved 1,200 papers written (or not) by 537 social-science and humanities undergraduates at a "selective post-secondary institution." Students in half of the courses involved in the study were required to participate in the plagiarism awareness tutorial via their Blackboard accounts, which included 18 pages of information about plagiarism followed by a quiz on the topic. It also provided advice about writing, including avoiding procrastination and taking careful notes. None of the students were made aware that they were participating in a study.
      </p>
      <p>
        Among the control group, 3.3 percent of papers met the researchers' criteria for plagiarism (using Turnitin), while the frequency of plagiarism for the Web tutorial group was about 1.3 percent. The Web tutorials, according to the researchers, were especially effective with one high-risk group in particular: those who had lower SAT scores coming into their institution. Using the data gathered in this study, the researchers predicted a "plagiarism rate of 17.7 percent among students at the national mean of SAT scores (i.e., 1017) and 31.4 percent among students at the 25th percentile of SAT scores (i.e., 850)."

Further, following the experiment, researchers conducted surveys with the students. "A follow-up survey of participating students suggests that the intervention reduced plagiarism by increasing student knowledge rather than by increasing the perceived probabilities of detection and punishment," according to the researchers. "These results are consistent with a model of student behavior in which the decision to plagiarize reflects both a poor understanding of academic integrity and the perception that the probabilities of detection and severe punishment are low."
      </p>
      <!-- Embedded Video -->
      <iframe width="560" height="315" src="https://www.youtube.com/embed/EraEV3aOMJc?si=pBxEywls6JFq2Efj" title="Plagiarism Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>
    <!-- Blog Section -->
    <section id="blog">
      <h2>Blog: Viruses, Malware, Spam, and Antiviruses</h2>
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
