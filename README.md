COMPANY: CODTECH IT SOLUTIONS

NAME: Rakshita Madival

INTERN ID: CTIS3674

DOMAIN: CLOUD COMPUTING

DURATION: 4 WEEKS

MENTOR: Neela Santosh Kumar


Task 3 — Multi-Cloud Object Delivery using AWS S3 + Cloudflare Workers
📌 Project Overview

This project demonstrates a multi-cloud workflow where an asset stored in AWS S3 is delivered to end users through Cloudflare Workers, improving edge delivery performance and reducing latency.

The Worker fetches the image stored in S3 and serves it directly to the client. This showcases multi-cloud integration and modern cloud operations practices that are useful in cloud support and distributed systems environments.

🎯 Objectives

✔ Deliver a private S3 object from AWS through Cloudflare’s global edge
✔ Implement multi-cloud interoperability (AWS → Cloudflare)
✔ Improve performance and caching using edge platforms
✔ Showcase cloud service configuration and integration skills

🧱 Architecture
Client → Cloudflare Worker → AWS S3 → Cloudflare Edge → Client

The solution uses:

AWS S3 for object storage

Cloudflare Workers for edge compute & delivery

IAM for access & permissions

JavaScript (Workers Runtime) for fetch logic

Public Object Serving via Cloudflare edge

Implementation Summary

Image uploaded to an S3 bucket

Permissions configured for object delivery

Cloudflare Worker created to fetch and serve the asset

Content rendered inline for direct viewing

Delivery tested through Cloudflare’s global network

📍 Outcome

Successfully delivered S3-hosted image directly through Cloudflare, demonstrating cloud interoperability, performance optimization, and serverless delivery.

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/7d8125ac-93e1-49f5-8375-6fdc2a146a10" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/2663359e-dae8-42c7-a36e-5a23e48ee5bf" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a0e311fb-b6e7-4a43-8e68-b8b4b8a6a854" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/94afc5eb-4e5e-4e8a-8923-86bca267a6e3" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0d3f1a7e-6be0-4d96-aa6b-9a39fb5293d4" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/209d3c90-05bf-4c25-a98b-01458884eb52" />
