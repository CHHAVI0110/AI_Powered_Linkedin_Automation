# AI LinkedIn Content Automation (Text + Image) using n8n

##  Overview

This project demonstrates an **AI-powered automation workflow built using n8n** that automatically generates **LinkedIn post text along with a relevant AI-generated image**.

The goal of this project is to show how AI agents and workflow automation can be combined to **save time, reduce manual effort, and ensure consistent content creation**.

This repository contains the exported **n8n workflow JSON**, documentation, and demo references.

---

##  Problem Statement

Creating high-quality LinkedIn content regularly is time-consuming. It requires:

* Writing professional post content
* Creating or sourcing relevant images
* Manually coordinating multiple tools

This project solves that problem by **automating the entire content creation pipeline** using AI and workflow orchestration.

---

##  Solution

The workflow:

1. Accepts user input through a form trigger
2. Generates a professional LinkedIn post using an AI agent
3. Creates an optimized image prompt using another AI agent
4. Generates an image via an external image generation API
5. Handles asynchronous processing using status polling
6. Automatically delivers the final text and image

The entire process runs without manual intervention after submission.

---

##  Key Features

* AI-generated LinkedIn captions
* AI-generated images aligned with the post content
* Multi-agent workflow design
* JavaScript-based data formatting
* API-based image generation
* Conditional logic and polling for reliability
* Fully automated delivery

---

##  Tech Stack

* **n8n** – Workflow automation
* **AI Agents / LLMs** – Content and prompt generation
* **JavaScript** – Data transformation and API payload handling
* **HTTP APIs** – Image generation and status checks
* **Conditional Logic** – Workflow reliability

---



---

##  Repository Structure

```
ai-linkedin-content-automation-n8n/
│
├── workflow.json        # Exported n8n workflow
├── README.md            # Project documentation
├── screenshots/         # Workflow screenshots
└── demo/                # Demo video link or notes
```


---

##  How to Use This Workflow

1. Install and run **n8n** (local or cloud)
2. Import `workflow.json` into n8n
3. Configure required API credentials
4. Submit the form trigger
5. Receive generated LinkedIn content automatically

---



⭐ If you find this project useful, feel free to star the repository
