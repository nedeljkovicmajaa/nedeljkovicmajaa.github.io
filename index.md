---
title: "Marija Nedeljković's CV"
layout: default
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marija Nedeljković's CV</title>
    <style>
        body {
            display: flex;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .sidebar {
            width: 250px;
            background-color: #f4f4f4;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            position: fixed;
            height: 100vh;
        }
        .sidebar img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .sidebar a {
            text-decoration: none;
            color: #333;
            margin: 10px 0;
            font-weight: bold;
        }
        .content {
            margin-left: 270px;
            padding: 20px;
            max-width: 800px;
        }
        .section {
            margin-bottom: 40px;
        }
        h1, h2 {
            color: #333;
        }
        @media (max-width: 768px) {
            body {
                flex-direction: column;
            }
            .sidebar {
                width: 100%;
                height: auto;
                position: static;
                padding-bottom: 20px;
            }
            .content {
                margin-left: 0;
            }
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <img src="your-photo.jpg" alt="Marija's photo">
        <h1>Marija Nedeljković</h1>
        <p><strong>Data Scientist | Machine Learning Enthusiast</strong></p>
        <p>10 Mileve Marić, Kraljevo 36212, Serbia</p>
        <p>📞 +381643304868</p>
        <p>✉️ <a href="mailto:nedeljkovicmajaa@gmail.com">nedeljkovicmajaa@gmail.com</a></p>
        <a href="https://www.linkedin.com/in/marija-nedeljkovic-b51328212/" target="_blank">LinkedIn</a> |
        <a href="https://github.com/nedeljkovicmajaa" target="_blank">GitHub</a>
        <hr>
        <a href="#education">Education</a>
        <a href="#publications">Publications</a>
        <a href="#experience">Work Experience</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#conferences">Conferences</a>
        <a href="#extracurricular">Extracurricular</a>
        <a href="#awards">Awards</a>
    </div>
    <div class="content">
        <div class="section" id="education">
            <h2>Education</h2>
            <h3>University of Cambridge</h3>
            <p><strong>MPhil in Data Intensive Science</strong> (Oct 2024 – July 2025), Cambridge, UK<br>
            Objective: Understanding data science and machine learning for practical research applications.</p>
            <h3>University of Belgrade, Faculty of Electrical Engineering</h3>
            <p><strong>B.Sc. in Electrical Engineering and Computing</strong> (Oct 2020 – July 2024), Belgrade, Serbia<br>
            - GPA: 9.15/10 (Top 5% of class)<br>
            - Relevant Modules: Pattern Recognition, Neural Networks, Signal and Image Processing, etc.</p>
     </div>
    <div class="section" id="publications">
            <h2>Publications</h2>
            <ul>
                <li><strong>Low-Dimensional EEG Classification for Alzheimer’s Disease Recognition</strong><br>
                Nedeljkovic M., Padin P. & Nikolic S., TELFOR Journal, vol.31, no.1, pp.201-205<br>
                Awarded Best Research Paper at University of Belgrade, 2023.</li>
                <li><strong>Radio-Frequency Localization</strong><br>
                Nedeljkovic M. & Stefanovic A., Petnica Journal, vol.78, no.1, pp.246-255</li>
            </ul>
        </div>
        <div class="section" id="experience">
            <h2>Work and Research Experience</h2>
            <h3>Biomedical Engineering Department, University of Belgrade</h3>
            <p><strong>Research Intern</strong> (Oct 2022 – Nov 2023)<br>
            - Analyzed EEG data of Alzheimer’s patients, using ML-based classifiers and dimensionality reduction.<br>
            - Developed software for tracking social interactions in Drosophila (collaborated with Pharmacological Institute).</p>     
            <h3>LMU and Max-Planck Institute for Biological Intelligence</h3>
            <p><strong>Amgen Scholar and Research Intern</strong> (July 2022 – Sept 2022), Munich, Germany<br>
            - Conducted research in computational neuroscience, focusing on neural network analysis and ML-based classification.</p>
            <h3>New Enterprise Associate (Remote, San Francisco, USA)</h3>
            <p><strong>Part-time Data Analyst</strong> (Mar 2022 – May 2022)<br>
            - Analyzed alternative data with Python, graph networks, Pandas, and SQL, optimizing data processing operations.</p>
        </div>
        <div class="section" id="skills">
            <h2>Skills</h2>
            <ul>
                <li><strong>Programming Languages:</strong> Python, R, SQL</li>
                <li><strong>Frameworks & Tools:</strong> TensorFlow, PyTorch, scikit-learn, Git, Notion</li>
            </ul>
        </div>
        <div class="section" id="projects">
            <h2>Projects</h2>
            <p><strong>Variational Autoencoders for Brain Lesion Segmentation</strong> (2024)<br>
            Compared architectures for unsupervised segmentation of brain lesions in MRI images.</p>
            <p><strong>Radio Frequency Localization</strong> (2019)<br>
            Developed a localization system using radio frequency antennas, achieving a relative error of 1.42%.</p>
            <p>For more, view my <a href="https://github.com/nedeljkovicmajaa" target="_blank">GitHub Projects</a>.</p>
        </div>
        <div class="section" id="conferences">
            <h2>Conferences and Seminars</h2>
            <ul>
                <li><strong>First Ascent by Bending Spoons</strong> (2024)<br>Participated in data science challenges.</li>
                <li><strong>TELFOR 31st Telecommunications Forum</strong> (2023)<br>Presented on EEG Classification for Alzheimer’s Disease.</li>
                <li><strong>Amgen Scholars Program Symposium</strong> (2022)<br>Presented a poster on auditory cortex neural representation.</li>
            </ul>
        </div>
        <div class="section" id="extracurricular">
            <h2>Extracurricular Activities</h2>
            <p><strong>Science and Engineering Center “PFE”</strong> (2019 – Present)<br>
            - Contributed to free education in AI, robotics, and applied physics.<br>
            - Organized over 25 seminars, supervised 10+ research projects, and led “PFEKV” club with 40+ members.</p>
            <p><strong>Undergraduate Teaching Assistant, University of Belgrade</strong> (2023 – 2024)<br>
            - Taught Object-Oriented Programming and signal processing in a lab environment.</p>
        </div>
        <div class="section" id="awards">
            <h2>Certifications & Awards</h2>
            <ul>
                <li>2nd Place in Robotic Hackathon</li>
                <li>Best Research Paper Award (University of Belgrade, 2024)</li>
                <li>Amgen Scholar (2022)</li>
            </ul>
        </div>
    </div>
</body>
</html>
