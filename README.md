<div align="center">
  <h2>🛠️ Languages & Technologies</h2>
</div>

<!-- Languages -->
<div align="center" class="grid-container">

  <a href="#" class="tech-badge">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&style=flat-square"/>
  </a>
</div>

<!-- Frameworks -->
<div align="center">
  <h3>🔧 Frameworks & Libraries</h3>
</div>

<div align="center" class="grid-container">
  <a href="#" class="tech-badge">
    <img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="Express.js" src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&style=flat-square"/>
  </a>
</div>

<!-- Databases -->
<div align="center">
  <h3>🗄️ Databases</h3>
</div>

<div align="center" class="grid-container">
  <a href="#" class="tech-badge">
    <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white&style=flat-square"/>
  </a>
</div>

<!-- Tools -->
<div align="center">
  <h3>🔨 Tools & Platforms</h3>
</div>

<div align="center" class="grid-container">
  <a href="#" class="tech-badge">
    <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white&style=flat-square"/>
  </a>

  <a href="#" class="tech-badge">
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white&style=flat-square"/>
  </a>
</div>

<style>
.grid-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  margin: 1rem 0;
}

.tech-badge {
  transition: all 0.3s ease;
  transform-style: preserve-3d;
  perspective: 1000px;
}

.tech-badge img {
  border-radius: 6px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
}

.tech-badge:hover {
  transform: translateY(-5px) rotateX(10deg);
}

.tech-badge:hover img {
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
  filter: brightness(1.1);
}

@keyframes float {
  0% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-5px);
  }
  100% {
    transform: translateY(0px);
  }
}

.tech-badge {
  animation: float 3s ease-in-out infinite;
}

.tech-badge:nth-child(odd) {
  animation-delay: 0.5s;
}

.tech-badge:nth-child(even) {
  animation-delay: 1s;
}

h2, h3 {
  background: linear-gradient(45deg, #12c2e9, #c471ed, #f64f59);
  -webkit-background-clip: text;
  color: transparent;
  margin: 2rem 0 1rem;
  font-weight: bold;
  text-transform: uppercase;
  letter-spacing: 2px;
}
</style>
