<template>
  <div>
    <div class="min-h-screen bg-base-200">
      <!-- Header -->
      <header class="navbar bg-base-100 shadow-lg flex-col md:flex-row">
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
      <main class="container mx-auto px-4 py-8">
        <!-- Hero Section -->
        <section class="hero min-h-screen bg-base-200">
          <div class="hero-content flex-col lg:flex-row-reverse">
            <div class="text-center lg:text-left w-full lg:w-1/2">
              <h1 class="text-4xl lg:text-5xl font-bold">Darshan Sawant</h1>
              <p class="py-2 text-xl lg:text-2xl">Senior Software Engineer</p>
              <p class="py-2">
                <a href="tel:+919967553216" class="link link-primary">+91 9967553216</a> |
                <a href="mailto:darshansawant1995@gmail.com" class="link link-primary">darshansawant1995@gmail.com</a>
              </p>
              <p class="py-2">
                <a href="https://www.linkedin.com/in/darshan-sawant-975128176/" target="_blank" class="link link-primary">LinkedIn</a> |
                <a href="https://github.com/SawantDarshan" target="_blank" class="link link-primary">GitHub</a>
              </p>
              <p class="py-2">Mumbai, Maharashtra</p>
              <div class="mt-6 flex flex-wrap justify-center lg:justify-start gap-4">
                <a href="#contact" class="btn btn-primary">Contact Me</a>
                <a href="#projects" class="btn btn-outline btn-secondary">View Projects</a>
              </div>
            </div>
            <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100 animate-fade-in-down mt-8 lg:mt-0">
              <div class="card-body">
                <h2 class="card-title mb-4 animate-pulse">Skills Highlight</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                  <div class="flex items-center animate-slide-in-right">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5" />
                    </svg>
                    Full Stack Dev
                  </div>
                  <div class="flex items-center animate-slide-in-left">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M5.25 14.25h13.5m-13.5 0a3 3 0 01-3-3m3 3a3 3 0 100 6h13.5a3 3 0 100-6m-16.5-3a3 3 0 013-3h13.5a3 3 0 013 3m-19.5 0a4.5 4.5 0 01.9-2.7L5.737 5.1a3.375 3.375 0 012.7-1.35h7.126c1.062 0 2.062.5 2.7 1.35l2.587 3.45a4.5 4.5 0 01.9 2.7m0 0a3 3 0 01-3 3m0 3h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008zm-3 6h.008v.008h-.008v-.008zm0-6h.008v.008h-.008v-.008z" />
                    </svg>
                    DevOps
                  </div>
                  <div class="flex items-center animate-slide-in-right">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 15a4.5 4.5 0 004.5 4.5H18a3.75 3.75 0 001.332-7.257 3 3 0 00-3.758-3.848 5.25 5.25 0 00-10.233 2.33A4.502 4.502 0 002.25 15z" />
                    </svg>
                    Cloud Technologies
                  </div>
                  <div class="flex items-center animate-slide-in-left">
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 mr-2">
                      <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3v11.25A2.25 2.25 0 006 16.5h2.25M3.75 3h-1.5m1.5 0h16.5m0 0h1.5m-1.5 0v11.25A2.25 2.25 0 0118 16.5h-2.25m-7.5 0h7.5m-7.5 0l-1 3m8.5-3l1 3m0 0l.5 1.5m-.5-1.5h-9.5m0 0l-.5 1.5m.75-9l3-3 2.148 2.148A12.061 12.061 0 0116.5 7.605" />
                    </svg>
                    Project Leadership
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="absolute bottom-10 left-1/2 transform -translate-x-1/2 hidden lg:block">
            <a href="#about" class="btn btn-circle btn-outline">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 8.25l-7.5 7.5-7.5-7.5" />
              </svg>
            </a>
          </div>
        </section>

        <!-- About Section -->
        <section id="about" class="py-16">
          <h2 class="text-3xl font-bold mb-8">About Me</h2>
          <div class="card bg-base-100 shadow-xl">
            <div class="card-body">
              <p>I'm a Senior Software Engineer with expertise in Full Stack Development, DevOps, and Cloud technologies. I have a proven track record of leading projects, improving efficiency, and implementing cutting-edge solutions in various domains including healthcare and business marketing.</p>
            </div>
          </div>
        </section>

        <!-- Experience Section -->
        <section id="experience" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Work Experience</h2>
          <div class="space-y-8">
            <div class="card bg-base-100 shadow-xl">
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
            <div class="card bg-base-100 shadow-xl">
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
            <div class="card bg-base-100 shadow-xl">
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
          <h2 class="text-3xl font-bold mb-8">Skills</h2>
          <div class="card bg-base-100 shadow-xl">
            <div class="card-body">
              <ul class="list-disc list-inside">
                <li><strong>Languages:</strong> JavaScript, SQL, Python, lua, golang, KQL, GraphQL</li>
                <li><strong>Frontend:</strong> HTML, CSS, React.js, Vue.js, Templating, EJS</li>
                <li><strong>Backend:</strong> Node.js, Express.js, Mongoose, Fastapi, go servers</li>
                <li><strong>Database:</strong> MYSQL, MongoDB, PostgreSQL, Redis</li>
                <li><strong>DevOps:</strong> Docker, Kubernetes, GitLab, AWS, Azure, Jenkins, Terraform</li>
                <li><strong>Cloud:</strong> AWS (Lambda, Athena, Glue, S3), Cloudflare</li>
                <li><strong>Soft Skills:</strong> Scrum Master, Agile Trainer, Team Leader, Cultural Manager</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Projects</h2>
          <div class="card bg-base-100 shadow-xl">
            <div class="card-body">
              <h3 class="card-title">Business Marketing Website</h3>
              <p>Created a high-class portfolio website (https://bmarketking.in/) for BMarketKing using React.js stack</p>
              <ul class="list-disc list-inside">
                <li>Implemented SEO mechanics to improve Google search rankings</li>
                <li>Utilized React.js for a responsive and dynamic user interface</li>
              </ul>
            </div>
          </div>
        </section>

        <!-- Education Section -->
        <section id="education" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Education</h2>
          <div class="space-y-4">
            <div class="card bg-base-100 shadow-xl">
              <div class="card-body">
                <h3 class="card-title">B.E. Electrical Engineering</h3>
                <p>Dilkap College (DRIEMS) | Apr 2019 | Mumbai, Maharashtra</p>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl">
              <div class="card-body">
                <h3 class="card-title">H.S.C. Science</h3>
                <p>Pendharkar College | Feb 2012 | Mumbai, Maharashtra</p>
              </div>
            </div>
            <div class="card bg-base-100 shadow-xl">
              <div class="card-body">
                <h3 class="card-title">S.S.C</h3>
                <p>Matoshri Vidyalaya High School | Mar 2010 | Mumbai, Maharashtra</p>
              </div>
            </div>
          </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-16">
          <h2 class="text-3xl font-bold mb-8">Contact Me</h2>
          <div class="card bg-base-100 shadow-xl">
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
      <footer class="footer footer-center p-4 bg-base-300 text-base-content">
        <div>
          <p>© 2024 Darshan Sawant - All rights reserved</p>
        </div>
      </footer>
    </div>
  </div>
</template>
