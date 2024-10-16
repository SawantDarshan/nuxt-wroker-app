<template>
  <div>
    <div class="min-h-screen bg-base-200 relative">
      <!-- Background Animation -->
      <div class="absolute inset-0 overflow-hidden pointer-events-none">
        <div id="node-graph-animation" class="w-full h-full opacity-40"></div>
      </div>

      <!-- Header -->
      <header class="navbar bg-base-100 shadow-lg flex-col md:flex-row relative z-10">
        <div class="flex-1">
          <a class="btn btn-ghost text-xl">Darshan Sawant</a>
        </div>
        <div class="flex-none w-full md:w-auto">
          <ul class="menu menu-horizontal px-1 flex-wrap justify-center">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
      </header>

      <!-- Main Content -->
      <main class="container mx-auto px-4 py-8 relative z-10">
        <!-- Hero Section -->
        <section class="hero min-h-screen bg-base-200">
          <div class="hero-content flex-col lg:flex-row-reverse">
            <div class="text-center lg:text-left w-full lg:w-1/2">
              <h1 class="text-4xl lg:text-5xl font-bold animate__animated animate__fadeInDown">Darshan Sawant</h1>
              <p class="py-2 text-xl lg:text-2xl animate__animated animate__fadeInUp">Senior Software Engineer</p>
              <p class="py-2 animate__animated animate__fadeIn">
                <a href="tel:+919967553216" class="link link-primary">+91 9967553216</a> |
                <a href="mailto:darshansawant1995@gmail.com" class="link link-primary">darshansawant1995@gmail.com</a>
              </p>
              <p class="py-2 animate__animated animate__fadeIn">
                <a href="https://www.linkedin.com/in/darshan-sawant-975128176/" target="_blank" class="link link-primary">
                  <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" class="inline-block">
                </a> |
                <a href="https://github.com/SawantDarshan" target="_blank" class="link link-primary">
                  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" class="inline-block">
                </a>
              </p>
              <p class="py-2 animate__animated animate__fadeIn">Mumbai, Maharashtra</p>
              <div class="mt-6 flex flex-wrap justify-center lg:justify-start gap-4">
                <a href="#contact" class="btn btn-primary animate__animated animate__bounceIn">Contact Me</a>
                <a href="#projects" class="btn btn-outline btn-secondary animate__animated animate__bounceIn">View Projects</a>
              </div>
            </div>
            <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100 mt-8 lg:mt-0 animate__animated animate__fadeInLeft">
              <div class="card-body">
                <h2 class="card-title mb-4">Skills Highlight</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5" />
                    </svg>
                    Full Stack Dev
                  </div>
                  <div class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 01-3-3m3 3a3 3 0 100 6h13.5a3 3 0 100-6m-16.5-3a3 3 0 013-3h13.5a3 3 0 013 3m-19.5 0a4.5 4.5 0 01.9-2.7L5.737 5.1a3.375 3.375 0 012.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 01.9 2.7m0 0a3 3 0 01-3 3m0 3h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008zm-3 6h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008z" />
                    </svg>
                    DevOps
                  </div>
                  <div class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 15a4.5 4.5 0 004.5 4.5H18a3.75 3.75 0 001.332-7.257 3 3 0 00-3.758-3.848 5.25 5.25 0 00-10.233 2.33A4.502 4.502 0 002.25 15z" />
                    </svg>
                    Cloud Technologies
                  </div>
                  <div class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 006 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0118 16.5h-2.25m-7.5 0h7.5m-7.5 0l-1 3m8.5-3l1 3m0 0l.5 1.5m-.5-1.5h-9.5m0 0l-.5 1.5m.75-9l3-3 2.148 2.148A12.061 12.061 0 0116.5 7.605" />
                    </svg>
                    Project Leadership
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 hidden lg:block animate__animated animate__bounce animate__infinite">
            <a href="#about" class="btn btn-circle btn-outline">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
              </svg>
            </a>
          </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">About Me</h2>
          <div class="card bg-base-100 shadow-xl animate__animated animate__fadeIn">
            <div class="card-body">
              <p>I'm a Senior Software Engineer with expertise in Full Stack Development, DevOps, and Cloud technologies. I have a proven track record of leading projects, improving efficiency, and implementing cutting-edge solutions in various domains including healthcare and business marketing.</p>
            </div>
          </div>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">Work Experience</h2>
          <div class="space-y-8">
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInLeft">
              <div class="card-body">
                <h3 class="card-title">Senior Software Engineer</h3>
                <p class="font-semibold">WebMD | May 2023 – Present | Mumbai, Maharashtra</p>
                <ul class="list-disc list-inside">
                  <li>Lead the Helios XaaS program for Full Stack Training</li>
                  <li>Improved frontend generator efficiency by 80%</li>
                  <li>Integrated Container Scanning and open-source projects</li>
                  <li>Implemented HIPAA architecture for webmdignite.com</li>
                </ul>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInRight">
              <div class="card-body">
                <h3 class="card-title">Software Engineer</h3>
                <p class="font-semibold">WebMD | Apr 2022 – May 2023 | Mumbai, Maharashtra</p>
                <ul class="list-disc list-inside">
                  <li>Created Vue Investigator platform</li>
                  <li>Integrated hashicorp for managing envvars and secrets</li>
                  <li>Developed Full Stack applications with Vue.js, Node.js, and PostgreSQL</li>
                  <li>Contributed to Infrastructure as Code (IAC) and DevOps practices</li>
                </ul>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInLeft">
              <div class="card-body">
                <h3 class="card-title">Junior Software Engineer</h3>
                <p class="font-semibold">WebMD | Dec 2021 – Apr 2022 | Mumbai, Maharashtra</p>
                <ul class="list-disc list-inside">
                  <li>Honored as Software Engineer and Employee of the Year</li>
                  <li>Integrated FormsFLow.Ai project for form automation</li>
                  <li>Upgraded WebMD helios website</li>
                  <li>Set up CI/CD pipelines for multiple projects</li>
                </ul>
              </div>
            </div>
          </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">Skills</h2>
          <div class="card bg-base-100 shadow-xl animate__animated animate__fadeIn">
            <div class="card-body">
              <ul class="list-disc list-inside">
                <li><strong>Languages:</strong> 
                  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=mysql&logoColor=white" alt="SQL" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go" class="inline-block">
                </li>
                <li><strong>Frontend:</strong> 
                  <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black" alt="React" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white" alt="Vue.js" class="inline-block">
                </li>
                <li><strong>Backend:</strong> 
                  <img src="https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white" alt="Node.js" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Express.js-000000?style=flat&logo=express&logoColor=white" alt="Express.js" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" class="inline-block">
                </li>
                <li><strong>Database:</strong> 
                  <img src="https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white" alt="MySQL" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" alt="MongoDB" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" class="inline-block">
                </li>
                <li><strong>DevOps:</strong> 
                  <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" alt="Kubernetes" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-GitLab-FCA121?style=flat&logo=gitlab&logoColor=white" alt="GitLab" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Jenkins-D24939?style=flat&logo=jenkins&logoColor=white" alt="Jenkins" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Terraform-623CE4?style=flat&logo=terraform&logoColor=white" alt="Terraform" class="inline-block">
                </li>
                <li><strong>Cloud:</strong> 
                  <img src="https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white" alt="AWS" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Azure-0089D6?style=flat&logo=microsoft-azure&logoColor=white" alt="Azure" class="inline-block mr-1">
                  <img src="https://img.shields.io/badge/-Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" alt="Cloudflare" class="inline-block">
                </li>
                <li><strong>Soft Skills:</strong> Scrum Master, Agile Trainer, Team Leader, Cultural Manager</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">Projects</h2>
          <div class="card bg-base-100 shadow-xl animate__animated animate__fadeIn">
            <div class="card-body">
              <h3 class="card-title">Business Marketing Website</h3>
              <p>Created a high-class portfolio website (https://bmarketking.in/) for BMarketKing using React.js stack</p>
              <ul class="list-disc list-inside">
                <li>Implemented SEO mechanics to improve Google search rankings</li>
                <li>Utilized React.js for a responsive and dynamic user interface</li>
              </ul>
              <img src="https://via.placeholder.com/400x200?text=Project+Screenshot" alt="Project Screenshot" class="mt-4 rounded-lg shadow-md">
            </div>
          </div>
        </section>

        <!-- Education Section -->
        <section id="education" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">Education</h2>
          <div class="space-y-4">
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInLeft">
              <div class="card-body">
                <h3 class="card-title">B.E. Electrical Engineering</h3>
                <p>Dilkap College (DRIEMS) | Apr 2019 | Mumbai, Maharashtra</p>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInRight">
              <div class="card-body">
                <h3 class="card-title">H.S.C. Science</h3>
                <p>Pendharkar College | Feb 2012 | Mumbai, Maharashtra</p>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl animate__animated animate__fadeInLeft">
              <div class="card-body">
                <h3 class="card-title">S.S.C</h3>
                <p>Matoshri Vidyalaya High School | Mar 2010 | Mumbai, Maharashtra</p>
              </div>
            </div>
          </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16">
          <h2 class="text-3xl font-bold mb-8 animate__animated animate__fadeInDown">Contact Me</h2>
          <div class="card bg-base-100 shadow-xl animate__animated animate__fadeIn">
            <div class="card-body">
              <p class="mb-4">Feel free to reach out to me:</p>
              <ul class="list-disc list-inside">
                <li>Email: <a href="mailto:darshansawant1995@gmail.com" class="link link-primary">darshansawant1995@gmail.com</a></li>
                <li>Phone: <a href="tel:+919967553216" class="link link-primary">+91 9967553216</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/darshan-sawant-975128176/" target="_blank" class="link link-primary">Darshan Sawant</a></li>
                <li>GitHub: <a href="https://github.com/SawantDarshan" target="_blank" class="link link-primary">SawantDarshan</a></li>
              </ul>
            </div>
          </div>
        </section>
      </main>

      <!-- Footer -->
      <footer class="footer footer-center p-4 bg-base-300 text-base-content relative z-10">
        <div>
          <p>© 2024 Darshan Sawant - All rights reserved</p>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import * as d3 from 'd3';

export default {
  mounted() {
    this.initNodeGraphAnimation();
  },
  methods: {
    initNodeGraphAnimation() {
      const width = window.innerWidth;
      const height = window.innerHeight;
      const nodeCount = 150; // Increased node count for more complexity
      const linkDistance = 100; // Reduced link distance for a more meshed appearance

      const svg = d3.select("#node-graph-animation")
        .append("svg")
        .attr("width", width)
        .attr("height", height);

      // Create a hierarchical structure for tree-like appearance
      const stratify = d3.stratify()
        .id(d => d.id)
        .parentId(d => d.parent);

      const treeData = d3.range(nodeCount).map(i => ({
        id: i,
        parent: i === 0 ? null : Math.floor((i - 1) / 3)
      }));

      const root = stratify(treeData);
      const nodes = root.descendants();
      const links = root.links();

      const simulation = d3.forceSimulation(nodes)
        .force("link", d3.forceLink(links).id(d => d.id).distance(linkDistance))
        .force("charge", d3.forceManyBody().strength(-100))
        .force("center", d3.forceCenter(width / 2, height / 2))
        .force("x", d3.forceX())
        .force("y", d3.forceY())
        .on("tick", ticked);

      const link = svg.selectAll(".link")
        .data(links)
        .enter().append("line")
        .attr("class", "link")
        .style("stroke", "#4a9ff5")
        .style("stroke-width", 1)
        .style("opacity", 0.8); // Increased opacity for better visibility

      const node = svg.selectAll(".node")
        .data(nodes)
        .enter().append("circle")
        .attr("class", "node")
        .attr("r", d => Math.max(3, 8 - d.depth)) // Vary node size based on depth
        .style("fill", d => d3.interpolateViridis(d.depth / 10)) // Color nodes based on depth
        .call(d3.drag()
          .on("start", dragstarted)
          .on("drag", dragged)
          .on("end", dragended));

      function ticked() {
        link
          .attr("x1", d => d.source.x)
          .attr("y1", d => d.source.y)
          .attr("x2", d => d.target.x)
          .attr("y2", d => d.target.y);

        node
          .attr("cx", d => d.x)
          .attr("cy", d => d.y);
      }

      function dragstarted(event, d) {
        if (!event.active) simulation.alphaTarget(0.3).restart();
        d.fx = d.x;
        d.fy = d.y;
      }

      function dragged(event, d) {
        d.fx = event.x;
        d.fy = event.y;
      }

      function dragended(event, d) {
        if (!event.active) simulation.alphaTarget(0);
        d.fx = null;
        d.fy = null;
      }

      window.addEventListener('resize', () => {
        const newWidth = window.innerWidth;
        const newHeight = window.innerHeight;
        svg.attr("width", newWidth).attr("height", newHeight);
        simulation.force("center", d3.forceCenter(newWidth / 2, newHeight / 2));
        simulation.alpha(1).restart();
      });
    }
  }
}
</script>

<style scoped>
#node-graph-animation {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
}
</style>
