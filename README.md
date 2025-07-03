<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚀 Fullstack Java Developer Portfolio</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            line-height: 1.6;
            color: #24292e;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #0366d6;
        }
        h1 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
        }
        h2 {
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
        }
        code {
            background-color: rgba(27, 31, 35, 0.05);
            border-radius: 3px;
            padding: 0.2em 0.4em;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
        }
        pre {
            background-color: #f6f8fa;
            border-radius: 3px;
            padding: 16px;
            overflow: auto;
        }
        .badge {
            display: inline-block;
            padding: 3px 6px;
            margin: 2px;
            border-radius: 3px;
            color: white;
            font-size: 0.85em;
        }
        .project-structure {
            background-color: #f6f8fa;
            padding: 16px;
            border-radius: 3px;
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, monospace;
            line-height: 1.45;
        }
    </style>
</head>
<body>
    <h1>🚀 Fullstack Java Developer Portfolio</h1>
    
    <p>Welcome to my Fullstack Java Developer repository! This project showcases my skills in building modern, scalable web applications using Java and popular frontend technologies.</p>
    
    <h2>🌟 Features</h2>
    <ul>
        <li><strong>Backend</strong>: Spring Boot, Microservices, REST APIs</li>
        <li><strong>Frontend</strong>: React/Thymeleaf, Bootstrap/Tailwind CSS</li>
        <li><strong>Database</strong>: PostgreSQL/MySQL, Hibernate/JPA</li>
        <li><strong>DevOps</strong>: Docker, Kubernetes, CI/CD Pipelines</li>
        <li><strong>Testing</strong>: JUnit, Mockito, TestNG</li>
    </ul>
    
    <h2>🛠️ Tech Stack</h2>
    
    <h3>Backend</h3>
    <span class="badge" style="background-color: #ED8B00;">Java</span>
    <span class="badge" style="background-color: #6DB33F;">Spring</span>
    <span class="badge" style="background-color: #F2F4F9; color: black;">Spring Boot</span>
    <span class="badge" style="background-color: #59666C;">Hibernate</span>
    
    <h3>Frontend</h3>
    <span class="badge" style="background-color: #20232A;">React</span>
    <span class="badge" style="background-color: #005F0F;">Thymeleaf</span>
    <span class="badge" style="background-color: #563D7C;">Bootstrap</span>
    
    <h3>Database</h3>
    <span class="badge" style="background-color: #316192;">PostgreSQL</span>
    <span class="badge" style="background-color: #005C84;">MySQL</span>
    
    <h3>DevOps</h3>
    <span class="badge" style="background-color: #2CA5E0;">Docker</span>
    <span class="badge" style="background-color: #326ce5;">Kubernetes</span>
    <span class="badge" style="background-color: #FF9900;">AWS</span>
    
    <h2>📂 Project Structure</h2>
    <div class="project-structure">
        fullstack-java/<br>
        ├── backend/               # Spring Boot application<br>
        │   ├── src/main/java      # Java source code<br>
        │   ├── src/main/resources # Config files<br>
        │   └── pom.xml           # Maven configuration<br>
        ├── frontend/              # React/Thymeleaf UI<br>
        │   ├── public/           # Static files<br>
        │   ├── src/              # React components<br>
        │   └── package.json      # NPM dependencies<br>
        ├── docker/               # Docker configurations<br>
        ├── kubernetes/           # K8s deployment files<br>
        └── README.md            # This file
    </div>
    
    <h2>🚀 Getting Started</h2>
    
    <h3>Prerequisites</h3>
    <ul>
        <li>Java 17+</li>
        <li>Maven 3.8+</li>
        <li>Node.js 16+</li>
        <li>Docker 20.10+</li>
    </ul>
    
    <h3>Installation</h3>
    <ol>
        <li>Clone the repo:
            <pre><code>git clone https://github.com/yourusername/fullstack-java.git
cd fullstack-java</code></pre>
        </li>
        <li>Build backend:
            <pre><code>cd backend
mvn clean install</code></pre>
        </li>
        <li>Run frontend:
            <pre><code>cd ../frontend
npm install
npm start</code></pre>
        </li>
        <li>Run with Docker:
            <pre><code>docker-compose up --build</code></pre>
        </li>
    </ol>
    
    <h2>🧪 Testing</h2>
    <p>Run unit tests:</p>
    <pre><code>mvn test</code></pre>
    
    <p>Run integration tests:</p>
    <pre><code>mvn verify -Pintegration</code></pre>
    
    <h2>🤝 Contributing</h2>
    <p>Pull requests are welcome! Please open an issue first to discuss what you'd like to change.</p>
    
    <h2>📜 License</h2>
    <p><a href="https://choosealicense.com/licenses/mit/">MIT</a></p>
    
    <h2>📫 Contact</h2>
    <p>
        <a href="https://linkedin.com/in/yourprofile" style="text-decoration: none;">
            <span class="badge" style="background-color: #0077B5;">LinkedIn</span>
        </a>
        <a href="mailto:youremail@gmail.com" style="text-decoration: none;">
            <span class="badge" style="background-color: #D14836;">Gmail</span>
        </a>
    </p>
    
    <h2>💡 Customization Tips</h2>
    <ol>
        <li>Replace placeholder links (<code>yourusername</code>, <code>yourprofile</code>, <code>youremail</code>) with your actual information</li>
        <li>Add screenshots of your projects in an <code>images/</code> folder and link them</li>
        <li>Include badges for specific technologies you've used</li>
        <li>Add a "Featured Projects" section highlighting your best work</li>
        <li>Consider adding a "Certifications" section if applicable</li>
    </ol>
</body>
</html>
