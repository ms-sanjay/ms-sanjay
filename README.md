<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sanjay M.S | Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet">
<style>
    body {
        font-family: 'Roboto', sans-serif;
        background: #f5f6fa;
        color: #2f3640;
        margin: 0;
        padding: 0;
    }
    .container {
        max-width: 900px;
        margin: auto;
        background: #fff;
        padding: 30px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        border-radius: 10px;
    }
    header {
        text-align: center;
        margin-bottom: 30px;
    }
    header h1 {
        margin: 0;
        font-size: 32px;
    }
    header p {
        font-size: 14px;
        color: #555;
    }
    .section {
        margin-bottom: 25px;
    }
    .section h2 {
        border-bottom: 2px solid #eee;
        padding-bottom: 5px;
        font-size: 20px;
        margin-bottom: 15px;
        color: #273c75;
    }
    .two-column {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 20px;
    }
    ul {
        list-style: none;
        padding: 0;
    }
    ul li {
        margin-bottom: 8px;
    }
    .logo-grid {
        display: flex;
        flex-wrap: wrap;
        gap: 15px;
    }
    .logo-grid img {
        height: 40px;
        width: auto;
        filter: grayscale(20%);
        transition: 0.3s;
    }
    .logo-grid img:hover {
        filter: grayscale(0%);
        transform: scale(1.05);
    }
</style>
</head>
<body>
<div class="container">

<header>
    <h1>Sanjay M.S</h1>
    <p>Passionate about building innovative solutions in both Software & Hardware domains</p>
</header>

<section class="section">
    <h2>Professional Summary</h2>
    <p>
        Electronics & Communication Engineer with strong skills in both hardware design and software development. 
        Experienced in embedded systems, IoT implementations, full-stack development, and cloud deployment. 
        Dedicated to problem-solving, continuous learning, and delivering impactful solutions.
    </p>
</section>

<section class="section">
    <h2>Skills</h2>
    <div class="logo-grid">
        <!-- Languages -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">

        <!-- Frameworks -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="ReactJS">
        
        <!-- Cloud -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS">

        <!-- IDEs -->
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" alt="IntelliJ IDEA">
    </div>
</section>

<section class="section two-column">
    <div>
        <h2>Software Expertise</h2>
        <ul>
            <li>Full-Stack Development (ReactJS, Java, REST APIs)</li>
            <li>Cloud Deployment (AWS EC2, S3, IoT Core)</li>
            <li>Database Management (MySQL, MongoDB)</li>
            <li>Version Control (Git, GitHub)</li>
        </ul>
    </div>
    <div>
        <h2>Hardware Expertise</h2>
        <ul>
            <li>Embedded Systems (STM32, ESP32, NodeMCU)</li>
            <li>IoT Prototyping (Sensors, Actuators, Communication Modules)</li>
            <li>PCB Design & Microcontroller Programming</li>
            <li>Serial Communication Protocols (UART, SPI, I2C)</li>
        </ul>
    </div>
</section>

<section class="section">
    <h2>Projects</h2>
    <ul>
        <li><b>IoT-based Emergency Alert & GPS Tracking System</b> – Implemented using ESP32, A9G GSM/GPS, MQTT.</li>
        <li><b>Smart Helmet</b> – Integrated accident detection & live location sharing using NodeMCU and sensors.</li>
        <li><b>Full-Stack Task Manager</b> – ReactJS frontend, Java backend, deployed on AWS EC2.</li>
    </ul>
</section>

<section class="section">
    <h2>Education</h2>
    <p>B.E. in Electronics & Communication Engineering – [Your College Name], [Year]</p>
</section>

</div>
</body>
</html>
