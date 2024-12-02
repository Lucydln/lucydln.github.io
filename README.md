<!-- Add styles for tabs -->
<style>
  .tab {
    overflow: hidden;
    border-bottom: 1px solid #ccc;
    background-color: #f1f1f1;
  }

  .tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
  }

  .tab button:hover {
    background-color: #ddd;
  }

  .tab button.active {
    background-color: #ccc;
  }

  .tabcontent {
    display: none;
    padding: 20px;
    border: 1px solid #ccc;
    border-top: none;
  }

  .tabcontent.active {
    display: block;
  }
</style>

<!-- Script to toggle tabs -->
<script>
  function openTab(evt, tabName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].className = tabcontent[i].className.replace(" active", "");
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(tabName).className += " active";
    evt.currentTarget.className += " active";
  }
</script>

# Luning Ding's Personal Website 🌟

<div align="center">
  <img src="https://github.com/user-attachments/assets/88375bd9-7f28-4978-a04b-42293f87041d" alt="Image description" width="200">
</div>

---

## Navigate My Profile
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'AboutMe')" id="defaultOpen">🌐 About Me</button>
  <button class="tablinks" onclick="openTab(event, 'Projects')">🚀 Featured Projects</button>
  <button class="tablinks" onclick="openTab(event, 'Skills')">🛠️ Technical Skills</button>
  <button class="tablinks" onclick="openTab(event, 'Experience')">🤝 Professional Experience</button>
  <button class="tablinks" onclick="openTab(event, 'Research')">📖 Research Experience</button>
</div>

<!-- About Me Section -->
<div id="AboutMe" class="tabcontent">
  <h2>🌐 About Me</h2>
  <p>
    🎓 Education: Pursuing a degree in <strong>Statistics and Data Science</strong> with a minor in <strong>Data Science Engineering</strong> at UCLA (Graduation: March 2025).
  </p>
  <p>📫 Let's Connect: Reach out via <strong>Email</strong>: lucydln66@gmail.com or <a href="http://linkedin.com/in/luning-ding-40543918b">LinkedIn</a>.</p>
</div>

<!-- Projects Section -->
<div id="Projects" class="tabcontent">
  <h2>🚀 Featured Projects</h2>
  <ul>
    <li><a href="https://github.com/Lucydln/Bee_Hair_Quantification">Bee Hair Quantification</a>: A computer vision tool for segmenting hair from bee images.</li>
    <li><a href="https://github.com/Lucydln/KMeans_Clustering_and_Pattern_Analysis_for_IPv4_Addresses">Kmeans-Clustering</a> and <a href="https://github.com/Lucydln/Confidence_Level_Analysis_For_IPv4_Addresses">Confidence Level Analysis</a>: Analyzing IPv4 data to prevent DDoS attacks.</li>
    <li><a href="https://github.com/Lucydln/CourseKata_Engagement_Optimization_Analysis">CourseKata Engagement Optimization Analysis</a>: Logistic regression model to improve e-learning engagement.</li>
    <li><a href="https://github.com/Lucydln/Cheat_Checker_Website">Cheat-Checker Website</a>: Eye-tracking web app for exam monitoring.</li>
    <li><a href="https://github.com/Lucydln/Image_Denoising_and_Filtering_Techniques">Image Denoising and Filtering Techniques</a>: Enhanced OCR accuracy for financial documents.</li>
    <li><a href="https://github.com/Lucydln/DetEval_For_OCR">DetEval For OCR</a>: Benchmarking OCR models with evaluation frameworks.</li>
  </ul>
  <p>Explore more of my projects <a href="https://github.com/Lucydln?tab=repositories">here</a>.</p>
</div>

<!-- Skills Section -->
<div id="Skills" class="tabcontent">
  <h2>🛠️ Technical Skills</h2>
  <p><strong>Programming Languages:</strong> Python, C++, SQL, R, HTML/CSS, MATLAB.</p>
  <p><strong>Frameworks & Libraries:</strong> PyTorch, TensorFlow, Scikit-Learn, Django.</p>
  <p><strong>Tools:</strong> Tableau, Jupyter Notebook, Git, AWS, Apache Spark, Docker.</p>
</div>

<!-- Experience Section -->
<div id="Experience" class="tabcontent">
  <h2>🤝 Professional Experience</h2>
  <h3>eBay Inc. (Data Analyst Intern) | June 2023 – September 2023</h3>
  <ul>
    <li>Developed dashboards and datacubes for analyzing over 50k listings.</li>
    <li>Enhanced financial analytics capabilities with SQL and Python.</li>
    <li>Streamlined data warehousing for efficient cross-department communication.</li>
  </ul>
  <h3>Hundsun Technologies Inc. (Machine Learning Engineer Intern) | July 2022 – September 2022</h3>
  <ul>
    <li>Improved OCR accuracy with image denoising and evaluation frameworks.</li>
    <li>Refined text detection models, boosting accuracy from 69% to 78%.</li>
  </ul>
  <h3>Zoom Video Communications (Data Engineer Intern) | January 2021 – April 2021</h3>
  <ul>
    <li>Analyzed IP data to mitigate DDoS attacks and automate transcoding tracking.</li>
    <li>Improved anomaly detection with advanced SQL and Python techniques.</li>
  </ul>
</div>

<!-- Research Section -->
<div id="Research" class="tabcontent">
  <h2>📖 Research Experience</h2>
  <h3>UCSB Cheadle Center for Biodiversity and Ecological Restoration (Research Intern) | September 2022–July 2024</h3>
  <ul>
    <li>Conducted research on bee hair quantification using computer vision.</li>
    <li>Improved segmentation and evaluation protocols, boosting accuracy to 89%.</li>
    <li>Published findings in Science and PNAS.</li>
  </ul>
</div>

<script>
  // Set default open tab
  document.getElementById("defaultOpen").click();
</script>
