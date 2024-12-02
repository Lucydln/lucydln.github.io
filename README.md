<!-- Add styles for tabs -->
<style>
  .tab {
    overflow: hidden;
    border-bottom: 1px solid #ccc;
    background-color: #f1f1f1;
    width: 100%;
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
    width: 25%; /* Each button now takes up 25% of the space */
    text-align: center;
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

# Welcome to Luning Ding's Personal Website 🌟

<div align="center">
  <img src="https://github.com/user-attachments/assets/88375bd9-7f28-4978-a04b-42293f87041d" alt="Luning Ding's profile picture" width="250">
</div>

Greetings! 👋 I am **Luning Ding**, a dedicated and innovative developer specializing in statistics, data science, machine learning, and software engineering. This website serves as a showcase for my projects, internships, and research.

---

## 🌐 About Me

🎓 Education: Pursuing a degree in **Statistics and Data Science** with a minor in **Data Science Engineering** at UCLA (Graduation: March 2025).

📫 Let's Connect: Reach out via **Email**: lucydln66@gmail.com or [LinkedIn](http://linkedin.com/in/luning-ding-40543918b).

---

## Navigate My Profile
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Projects')" id="defaultOpen">🚀 Featured Projects</button>
  <button class="tablinks" onclick="openTab(event, 'Experience')">🤝 Professional Experience</button>
  <button class="tablinks" onclick="openTab(event, 'Research')">📖 Research Experience</button>
  <button class="tablinks" onclick="openTab(event, 'Skills')">🛠️ Technical Skills</button>
</div>

<!-- Projects Section -->
<div id="Projects" class="tabcontent">
  <h2>🚀 <a href="https://github.com/Lucydln">Featured Projects</a></h2>

  <h3><a href="https://github.com/Lucydln/Bee_Hair_Quantification">Bee Hair Quantification</a></h3>
  <ul>
    <li><strong>About</strong>: A computer vision tool for segmenting hair from images of bees and quantifying hairiness.</li>
    <li><strong>Technologies Used</strong>: Python, PyTorch, OpenCV, Scikit-Image.</li>
    <li><strong>Impact</strong>: Provided valuable insights into bee morphology and its role in climate adaptability through advanced image analysis techniques.</li>
    <li><a href="https://advance.sagepub.com/users/515590/articles/1215597-climate-explains-global-functional-trait-variation-in-bees#"><strong>Published Research Paper Here</strong></a></li>
  </ul>

  <h3><a href="https://github.com/Lucydln/KMeans_Clustering_and_Pattern_Analysis_for_IPv4_Addresses">Kmeans-Clustering</a> and <a href="https://github.com/Lucydln/Confidence_Level_Analysis_For_IPv4_Addresses">Confidence Level Analysis</a> for IPv4 Addresses</h3>
  <ul>
    <li><strong>Objective</strong>: Analyzed large-scale IP whitelist data using K-means clustering and confidence level analysis to identify patterns and prevent DDoS attacks.</li>
    <li><strong>Technologies Used</strong>: Python, Scikit-Learn, SQL.</li>
    <li><strong>Impact</strong>: Enhanced system security and streamlined data processing pipelines.</li>
  </ul>

  <h3><a href="https://github.com/Lucydln/CourseKata_Engagement_Optimization_Analysis">CourseKata Engagement Optimization Analysis</a></h3>
  <ul>
    <li><strong>Objective</strong>: Built a logistic regression model to analyze e-learning engagement data and identify key drivers of student performance.</li>
    <li><strong>Technologies Used</strong>: R, Python, ggplot2, Matplotlib.</li>
    <li><strong>Recognition</strong>: Awarded the <strong>DataFest Outstanding Project Award</strong>.</li>
    <li><a href="https://github.com/Lucydln/CourseKata_Engagement_Optimization_Analysis/blob/main/final%20presentation.pdf"><strong>Presentation Slides Here</strong></a></li>
  </ul>

  <h3><a href="https://github.com/Lucydln/Cheat_Checker_Website">Cheat-Checker Website</a></h3>
  <ul>
    <li><strong>Objective</strong>: Developed a web app for teachers to flag suspicious activities during exams using eye-tracking models.</li>
    <li><strong>Technologies Used</strong>: TensorFlow, Django, HTML, CSS.</li>
    <li><strong>Recognition</strong>: Awarded the <strong>SBHacks Most Creative Project Award</strong>.</li>
  </ul>

  <h3><a href="https://github.com/Lucydln/Image_Denoising_and_Filtering_Techniques">Image Denoising and Filtering Techniques</a></h3>
  <ul>
    <li><strong>Objective</strong>: Explored various denoising and filtering methods to enhance OCR accuracy for large-scale document datasets.</li>
    <li><strong>Technologies Used</strong>: TensorFlow, Python, OpenCV.</li>
    <li><strong>Context</strong>: Part of Hundsun Technologies internship, where I developed a pipeline for preprocessing scanned financial document images, significantly improving data extraction performance.</li>
  </ul>

  <h3><a href="https://github.com/Lucydln/DetEval_For_OCR">DetEval For OCR</a></h3>
  <ul>
    <li><strong>Objective</strong>: Implemented a comprehensive evaluation framework to benchmark OCR accuracy using real-world scanned financial documents.</li>
    <li><strong>Technologies Used</strong>: Python, PyTorch.</li>
    <li><strong>Context</strong>: During my internship at Hundsun Technologies, I utilized this tool to assess and improve document classification models, achieving higher reliability in text recognition tasks.</li>
  </ul>

  <p>Explore more of my projects <a href="https://github.com/Lucydln?tab=repositories">here</a>.</p>
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
    <li>Published research paper can be found <a href="https://advance.sagepub.com/users/515590/articles/1215597-climate-explains-global-functional-trait-variation-in-bees#">here</a>.</li>
  </ul>
</div>


<!-- Skills Section -->
<div id="Skills" class="tabcontent">
  <h2>🛠️ Technical Skills</h2>
  <p><strong>Programming Languages:</strong> Python, C++, SQL, R, HTML/CSS, MATLAB.</p>
  <p><strong>Frameworks & Libraries:</strong> PyTorch, TensorFlow, Scikit-Learn, Django.</p>
  <p><strong>Tools:</strong> Tableau, Jupyter Notebook, Git, AWS, Apache Spark, Docker.</p>
</div>

<script>
  // Set default open tab
  document.getElementById("defaultOpen").click();
</script>
