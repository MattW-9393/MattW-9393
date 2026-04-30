# Matt Warne

IT professional transitioning into cloud infrastructure and solutions architecture. I have a background in IT Service Delivery and am actively building towards a career in DevOps, SRE, or cloud engineering — with hands-on experience across the full deployment lifecycle: application development, containerisation, infrastructure as code, and CI/CD automation.

---

## Certifications

**AWS Solutions Architect — Associate (SAA-C03)**
Validated knowledge of AWS core services, networking, security, and architectural best practices across compute, storage, database, and deployment services.

---

## Technical Skills

| Area | Technologies |
|---|---|
| Languages | Python, HTML, CSS, JavaScript |
| Frameworks | Flask, WTForms, Jinja2 |
| Cloud | AWS (ECS Fargate, ECR, ALB, S3, CloudWatch, IAM, ACM) |
| Infrastructure as Code | Terraform |
| Containers | Docker, Gunicorn |
| CI/CD | GitHub Actions, OIDC authentication |
| Version Control | Git, GitHub |
| Currently exploring | PostgreSQL, Aurora Serverless, user auth, React |

---

## Featured Projects

### 🏏 Bat or Brolly
*A cricket weather verdict app — fully deployed on AWS with production-grade infrastructure*

Bat or Brolly answers the question every village cricketer asks on a Saturday morning: is it worth making the trip to the ground? Enter a UK location, get a plain-English verdict based on cricket-specific weather thresholds.

The primary purpose of this project was to demonstrate the full deployment lifecycle — from a working Flask application through to a containerised, cloud-deployed service with automated CI/CD.

**What it demonstrates:**
- Full-stack Python development (Flask, Jinja2, WTForms, REST API integration)
- Docker containerisation with a production WSGI server (Gunicorn)
- AWS ECS Fargate deployment behind an Application Load Balancer
- Infrastructure as Code with Terraform — remote state in S3, DynamoDB locking
- GitHub Actions CI/CD pipeline with OIDC authentication (no long-lived credentials)
- SHA-tagged immutable Docker images for full deployment traceability
- Deliberate architectural decisions documented in the project README

**Tech:** Python · Flask · Docker · AWS ECS Fargate · ALB · ECR · Terraform · GitHub Actions

[View project →](https://github.com/MattW-9393/bat-or-brolly) 
[View live app →](http://bat-or-brolly-dev-alb-536497550.eu-west-2.elb.amazonaws.com/bat_or_brolly?location=whdk)

---

### 📓 Stratus *(in development)*
*A personal metrics and journaling app with OCR pipeline*

Stratus is a daily mood and wellbeing tracker with an integrated OCR pipeline — photograph a handwritten journal entry and it gets automatically extracted and linked to that day's metrics. Built to demonstrate database design, async processing, and a more complex AWS architecture than Bat or Brolly.

**Planned architecture:**
- Flask backend with PostgreSQL on Aurora Serverless v2
- AWS Textract for handwritten OCR
- SQS queue for async image processing
- S3 for image storage with lifecycle policies
- Full user authentication
- Mobile-first UI

**Tech:** Python · Flask · Aurora Serverless · AWS Textract · SQS · S3 · Terraform · Docker

*Active development — architecture documented, build in progress.*

---

### 💪 Optex *(live)*
*A workout builder application*

A frontend web application for creating and storing custom workout routines. Built as an early project to develop JavaScript fundamentals — dynamic UI generation, state management, and local data persistence.

**Tech:** HTML · CSS · JavaScript

[View project →](https://github.com/MattW-9393)

---

## Currently Learning

- Linux service management — systemd, nginx configuration, log management
- Networking fundamentals — DNS, reverse proxies, firewall rules, VPN (WireGuard)
- Kubernetes fundamentals via k3s on Raspberry Pi 5
- PostgreSQL and relational database design

---

## Background

I have spent several years in IT Service Delivery, managing technical teams and leading infrastructure improvement programmes. That background gives me an understanding of how technology decisions affect real operations — something I think is undervalued in purely technical roles.

I am now building the hands-on technical depth to match that operational experience, with a focus on cloud infrastructure, DevOps tooling, and solutions architecture. The AWS SAA certification and Bat or Brolly project represent the foundation of that transition — the work above represents where it is going.

In my spare time, when I'm not coding, I enjoy playing cricket, going to the gym, Muay Thai, and playing RPG video games. 

---

## Contact

- 💼 [LinkedIn](https://www.linkedin.com/in/matt-warne-227863342)
- 📝 [Blog](https://cloudlog-matt.hashnode.dev/)
- 📫 [matt.warne22@gmail.com](mailto:matt.warne22@gmail.com)
