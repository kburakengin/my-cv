---
layout: cv
title: Kadir Burak Engin — CV
---
# Kadir Burak Engin
Backend & Infrastructure Developer — Node.js · TypeScript · AWS · CI/CD

## Contact

- kburakengin@gmail.com
- [linkedin.com/in/kburakengin](https://linkedin.com/in/kburakengin)
- [github.com/kburakengin](https://github.com/kburakengin)
- [mobeat.io](https://mobeat.io)

## Summary

Backend & infrastructure developer with 5+ years building and operating production systems at scale, specializing in resilient backend architecture, cloud infrastructure on AWS, and the CI/CD and monitoring that keep services stable under load. I currently own the backend and infrastructure for a mobile app with ~4M registered users, and shipped Mobeat.io, a production analytics platform, end-to-end on AWS.

## Experience

`Sep 2021 – Present`
__Backend & Infrastructure Developer__, Gamester Kids — Istanbul (Remote)

*"Tiny Minies" — kids' mobile game (Firebase / Firestore, Node.js / TypeScript)*

- Own the backend and infrastructure for a production service with ~4M registered users, 786K+ active in the last 12 months, and 673K+ installs over the same period.
- Handle production API traffic of ~64K requests/day, optimizing Firestore queries and data models to keep latency low as usage grew.
- Designed complex Firestore schemas and data flows, balancing read/write performance and cost at scale; migrated the support backend from JavaScript to TypeScript.
- Implemented App Store & Google Play server-side notifications (RTDN) and integrated MMP services via webhooks to track subscriptions and revenue.
- Authored a custom open-source GitHub Action ([firebase-functions-deploy](https://github.com/kburakengin/firebase-functions-deploy), on GitHub Marketplace) enabling selective Firebase Functions deployment — shipping only changed functions instead of the entire set.
- Automated Firebase hosting/functions deployment and instrumented Sentry monitoring, resulting in no major incidents in production.

`Feb 2022 – Present`
__Founder & Lead Developer__, [Mobeat.io](https://mobeat.io) — Remote

*Subscription analytics & revenue platform for mobile app teams (live in production)*

- Designed and built the full platform end-to-end: React + Material UI frontend, a Node.js / TypeScript API on AWS Elastic Beanstalk (Dockerized via ECR), and AWS Lambda + SQS for asynchronous store webhooks (RTDN), scheduled jobs, and event processing.
- Architected the data layer with PostgreSQL (Sequelize ORM, RDS in production) and Redis caching for chart and API performance.
- Built a fully automated CI/CD pipeline in GitHub Actions deploying to ECR for both the Elastic Beanstalk API and Lambda functions.
- Set up CloudWatch alarm-driven scaling with EBS auto-scaling — no major incidents for ~12 months in production — and reduced AWS costs by right-sizing infrastructure.

## Selected Project

`2024–2025`
__B2B Financial Operations Platform__ — Python backend (client project)

- Co-developed a production Python backend: FastAPI with async SQLAlchemy (PostgreSQL), Redis, and Kafka / RabbitMQ for event-driven messaging, on AWS & Kubernetes (EKS, Helm, Terraform) with OpenTelemetry, Prometheus & Sentry observability.
- Built AWS SES email-template tooling (boto3) reusing the app's service layer; integrated S3 and Auth0.

## Earlier Experience

`2020–2021`
__Java / SAP Commerce (Hybris) Developer__, BTC IT Services — e-commerce globalization, B2B features (Spring Boot, Hibernate, Angular).

`2017–2020`
__Brand Manager__, Studio Fashion Agency

## Skills

- __Languages:__ TypeScript, JavaScript (Node.js), Python, SQL, Java
- __Backend:__ Node.js, Express, FastAPI, REST APIs, event-driven architecture, message queues (SQS, Kafka, RabbitMQ), webhooks, data modeling
- __Cloud & Infrastructure:__ AWS (Lambda, SQS, Elastic Beanstalk, ECR, RDS, S3, SES, Cognito, CloudWatch), GCP / Firebase
- __DevOps:__ Docker, Kubernetes, Terraform, CI/CD, GitHub Actions, monitoring & observability (CloudWatch, Sentry, OpenTelemetry, Prometheus)
- __Databases:__ PostgreSQL, Firestore, Redis, Sequelize (ORM)
- __Frontend:__ React, Material UI, Redux Toolkit

## Education

`2020–2024`
__B.Sc. Management Information Systems__, Istanbul University

`2011–2015`
__B.A. Public Administration__, Muğla Sıtkı Koçman University

## Certifications

__Python Software Development__ — Arı Bilgi IT Academy (Django, ML, data manipulation)

## Languages

- English — Professional Working
- Turkish — Native
