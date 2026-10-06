<br />
<div id="header" align="center">
  <img src="/Home.gif" width="200" height="200"/>
</div>
<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/djallal-me/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://djmekki.com/">
    <img src="https://img.shields.io/badge/Website-red?style=for-the-badge&logo=Google%20Chrome&logoColor=white" alt="Website Badge"/>
  </a>
  <a href="https://profile.intra.42.fr/users/djmekki">
    <img src="https://img.shields.io/badge/intra-black?style=for-the-badge&logo=42&logoColor=white" alt="42 Intra Badge"/>
  </a>
</div>
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=djedd1ne&style=flat-square&color=red" alt=""/>
</div>

<h1>
  Hey there, I'm Djallal!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

### Backend developer: Go, Python, REST APIs, Docker and the cloud

I started out as a petroleum engineer and switched to software through **42 Heilbronn**. There are no teachers there, only projects, peers and a lot of debugging. What I enjoy most is the part users never see: APIs, data, auth, and getting services to run reliably in containers and in the cloud.

At **SCHUNK** I build backend services for Industry 4.0 digital twins. I work from the SCHUNK office at **IPAI** (Innovation Park Artificial Intelligence) in Heilbronn, where I was also part of the IPAI AI User Circle. I completed Level 3 of the **Arkadia Heilbronn Digital Twins** track.

## 🏭 What I'm building at SCHUNK

- **A product data microservice.** I wrote aas-creator in Python with FastAPI. It takes product master data from spreadsheets, validates it, and turns it into standardized digital twin packages (AASX and JSON). Users can download the result, and admins can publish it to the registry, with access controlled through Keycloak JWT roles. It has already caught real data entry errors in the source data.
- **A move from self-hosted to Google Cloud.** I moved a containerized Eclipse BaSyx stack (Keycloak, a Spring Boot API and a Vue UI) from Docker Compose to Cloud Run, Cloud SQL Postgres, MongoDB Atlas and a global HTTPS load balancer. Most of the work was debugging what broke along the way: JWT issuer mismatches behind a proxy, CORS and redirect loops, TLS certificates, database drivers, and an nginx limit that silently cut off file uploads.
- **Security from the start.** OIDC login and role-based access with Keycloak, service accounts for automated imports, and TLS behind nginx.
- **Product data from real systems.** I map product data from the company PIM and databases into structured models. This is the same kind of catalog data that powers an online shop.
- **Docs and demos.** I wrote an 11-chapter reference guide on the AAS metamodel for the team, and I present my work in agile increments with a ranked backlog and milestones.

## 🚀 About Me

- 🛒 Learning PHP and Symfony right now by building **marketplace-lite**, a small marketplace with a Go catalog service and a Symfony storefront
- 🤖 I've spent a year evaluating AI generated code as an AI trainer, so I use AI tools a lot, and I check what they write
- 🔐 Security minded: HTB CTF team 3rd place and an EC-Council DevSecOps certificate
- 🧠 Always curious about how products are built, not just the code behind them
- 💼 Open to backend roles

## 📂 What You'll Find Here

| Project | What it does | Stack |
|---|---|---|
| [marketplace-lite](https://github.com/djedd1ne/marketplace-lite) | Sellers upload product feeds, a Go service validates them and serves the catalog over REST, and a Symfony storefront shows the offers | Go, PHP, Symfony, PostgreSQL, Docker, GitHub Actions |
| [go-webhook-gateway](https://github.com/djedd1ne/Coding_Challenge) | Receives events on a REST webhook and forwards them to the Telegram Bot API | Go, gorilla/mux |
| [inception](https://github.com/djedd1ne/inception) | nginx with TLS, MariaDB and WordPress, each in its own container | Docker, Docker Compose, nginx |
| [ft_transcendence](https://github.com/nichtsbesonders/ft_transcendence) | Team project: real time multiplayer 3D Pong with live chat and 42 login | Django, React, Three.js, WebSockets |

Plus my 42 projects in C and C++: a shell, a ray-casting 3D engine, a 2D game and more.

## ⚡ Fun Fact

I share a birthday with Albert Einstein (March 14th), though he was nothing like me! 🎂🧠

### :hammer_and_wrench: Languages and Tools

**Backend**<br/>
<img src="https://github.com/devicons/devicon/blob/master/icons/go/go-original-wordmark.svg" title="Go" alt="Go" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/fastapi/fastapi-original.svg" title="FastAPI" alt="FastAPI" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="PHP" alt="PHP" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/symfony/symfony-original.svg" title="Symfony" alt="Symfony" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/nginx/nginx-original.svg" title="nginx" alt="nginx" width="40" height="40"/>&nbsp;

**Databases**<br/>
<img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg" title="PostgreSQL" alt="PostgreSQL" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original.svg" title="MongoDB" alt="MongoDB" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL" alt="MySQL" width="40" height="40"/>

**Cloud and DevOps**<br/>
<img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain.svg" title="Docker" alt="Docker" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/podman/podman-original.svg" title="Podman" alt="Podman" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/kubernetes/kubernetes-original.svg" title="Kubernetes" alt="Kubernetes" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/googlecloud/googlecloud-original.svg" title="Google Cloud" alt="Google Cloud" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/azure/azure-original.svg" title="Azure" alt="Azure" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="Linux" alt="Linux" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg" title="Bash" alt="Bash" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" alt="Git" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/githubactions/githubactions-original.svg" title="GitHub Actions" alt="GitHub Actions" width="40" height="40"/>

**Frontend**<br/>
<img src="https://github.com/devicons/devicon/blob/master/icons/vuejs/vuejs-original-wordmark.svg" title="Vue.js" alt="Vue.js" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/vuetify/vuetify-original.svg" title="Vuetify" alt="Vuetify" width="40" height="40"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/threejs/threejs-original.svg" title="Three.js" alt="Three.js" width="40" height="40"/>
