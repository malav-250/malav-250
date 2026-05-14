<h1 align="center">Malav Gajera</h1>
<h3 align="center">Backend &amp; Cloud Engineer · MS @ Northeastern</h3>

<p align="center">
  <a href="https://malavgajera.is-a.dev">
    <img src="https://img.shields.io/badge/Portfolio-malavgajera.is--a.dev-06b6d4?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://malavgajera.is-a.dev/blog">
    <img src="https://img.shields.io/badge/Blog-Notes_on_backend_systems-3b82f6?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Blog" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/malav-gajera-884003202/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:gajera.ma@northeastern.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://malavgajera.is-a.dev/resume.pdf">
    <img src="https://img.shields.io/badge/Resume-PDF-1f2937?style=flat&logo=adobeacrobatreader&logoColor=white" alt="Resume" />
  </a>
</p>

---

### About

MS in Computer Software Engineering @ **Northeastern University** (3.9 GPA), graduating **December 2026**.
Currently a **Software Engineer Co-op** at **Crewasis**, building AI-marketing infrastructure.

I focus on backend services, cloud infrastructure, and the CI/CD that ties them together — Python, Java, AWS, PostgreSQL, Terraform.

**Open to full-time Backend / Cloud Engineering roles starting January 2027.**

---

### Featured case studies

Each project has a written case study with architecture diagrams, key decisions, and trade-offs.

<table>
  <tr>
    <td valign="top" width="50%">
      <h4>🚀 <a href="https://malavgajera.is-a.dev/projects/distributed-task-queue">Distributed Task Queue</a></h4>
      <p><b>Celery + RabbitMQ — Circuit Breakers, Observability, Terraform</b></p>
      <p>Production-grade task queue with dead-letter routing, idempotency keys, Redis-backed circuit breakers, and a Prometheus/Grafana observability stack. 8 services containerized via Docker Compose, deployed to ECS Fargate via Terraform.</p>
      <p><a href="https://github.com/malav-250/distributed-task-queue">Repo</a> · <a href="https://malavgajera.is-a.dev/projects/distributed-task-queue">Case study</a> · <a href="https://malavgajera.is-a.dev/blog/dead-letter-routing">Blog post</a></p>
    </td>
    <td valign="top" width="50%">
      <h4>📞 <a href="https://malavgajera.is-a.dev/projects/voice-agent">Real-Time AI Voice Agent</a></h4>
      <p><b>Sub-Second Phone Conversations — Streaming STT + LLM + TTS</b></p>
      <p>Voice agent handling real phone calls. Streaming pipeline over Twilio Media Streams with interrupt-aware router + barge-in support, so the caller can cut the agent off mid-sentence.</p>
      <p><a href="https://github.com/malav-250/deepgram-voice-agent">Repo</a> · <a href="https://malavgajera.is-a.dev/projects/voice-agent">Case study</a></p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <h4>☁️ <a href="https://malavgajera.is-a.dev/projects/cloud-native-app">Resilient Cloud Deployment Platform</a></h4>
      <p><b>Full AWS Stack — Terraform IaC, Multi-AZ, Blue-Green CI/CD</b></p>
      <p>3-repo platform: FastAPI service, Terraform IaC for the full AWS topology, and serverless email verification. Multi-AZ Auto Scaling Group behind an ALB with blue-green deployments via AMI bake.</p>
      <p><a href="https://github.com/malav-250/cloud-webapp">Web</a> · <a href="https://github.com/malav-250/cloud-tf-aws-infra">Infra</a> · <a href="https://github.com/malav-250/cloud-serverless">Serverless</a> · <a href="https://malavgajera.is-a.dev/projects/cloud-native-app">Case study</a></p>
    </td>
    <td valign="top" width="50%">
      <h4>🚗 <a href="https://malavgajera.is-a.dev/projects/transportation-platform">Vehicle Rental Microservices Platform</a></h4>
      <p><b>Spring Boot — Concurrent Booking with Transactional Locks</b></p>
      <p>Ride-booking platform on Spring Boot microservices. Row-level pessimistic locks prevent double-booking under contention; Redis caches the high-read paths so the database isn&apos;t hammered.</p>
      <p><a href="https://github.com/malav-250/transportation-platform">Repo</a> · <a href="https://malavgajera.is-a.dev/projects/transportation-platform">Case study</a></p>
    </td>
  </tr>
</table>

---

### Latest writing

[![Latest blog post](https://img.shields.io/badge/📝_Latest-Designing_dead--letter_routing_for_a_distributed_task_queue-06b6d4?style=for-the-badge)](https://malavgajera.is-a.dev/blog/dead-letter-routing)

Why naive Celery retries silently drop messages, and the RabbitMQ DLX patterns that keep every failure observable and replayable. → [Read on the blog](https://malavgajera.is-a.dev/blog/dead-letter-routing)

---

### What I work with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Backend &amp; APIs**

![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)

**Cloud &amp; DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=flat&logo=packer&logoColor=white)

**Databases &amp; caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)

---

### GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=malav-250&show_icons=true&theme=default&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=malav-250&layout=compact&theme=default&hide_border=true" height="165" alt="Top Languages" />
</p>

---

<p align="center">
  <i>Open to full-time <b>Backend / Cloud Engineering</b> roles starting <b>January 2027</b>.</i>
  <br/>
  📩 <a href="mailto:gajera.ma@northeastern.edu">gajera.ma@northeastern.edu</a> · <a href="https://malavgajera.is-a.dev"><b>malavgajera.is-a.dev</b></a>
</p>
