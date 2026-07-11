# 🚀 AI-Powered LinkedIn Content Automation System

An end-to-end **LinkedIn Content Automation System** built with **n8n** that leverages AI to automate the complete content creation workflow—from topic research to LinkedIn-ready posts and AI-generated visuals.

This project demonstrates how AI agents and workflow automation can streamline content creation while keeping a human approval step before publishing.

---

## 📌 Project Overview

Creating engaging LinkedIn content consistently takes time and effort. This automation simplifies the process by using AI to research a topic, generate a professional LinkedIn post, create an image prompt, generate a matching image, and either publish the content automatically or send it to Gmail for manual approval.

---

## ✨ Features

- 🔍 AI-powered topic research
- ✍️ AI-generated LinkedIn posts
- 🎨 AI image prompt generation
- 🖼️ AI image generation
- 📧 Gmail approval workflow
- 🔄 Optional automatic LinkedIn publishing
- ⚡ Fully automated with n8n

---

# 🏗️ Workflow

```text
Google Form
      │
      ▼
Research Agent
      │
      ▼
LinkedIn Post Generator
      │
      ▼
Image Prompt Generator
      │
      ▼
Image Generator
      │
      ▼
Send Gmail

---

# 🛠️ Tech Stack

- **n8n**
- **Google Gemini**
- **Forms**
- **Gmail**
- **LinkedIn API**
- **HTTP Request Nodes**
- **AI Agents**

---

# 📋 Workflow Breakdown

## 1️⃣ User Submission

The workflow begins with an **n8n Form** where users provide:

- Content Topic
- Target Audience

---

## 2️⃣ AI Research Agent

The Research Agent gathers information related to the topic and identifies:

- Key insights
- Current trends
- Important facts
- Content ideas

---

## 3️⃣ LinkedIn Post Generator

Using the research, AI creates a complete LinkedIn post including:

- Attention-grabbing hook
- Valuable content
- Call-to-action
- Relevant hashtags

---

## 4️⃣ Image Prompt Generator

AI generates a detailed prompt optimized for AI image generation.

Example:

> A modern isometric illustration showing AI automation workflows using n8n, professional blue color palette, clean background, minimal style, high quality.

---

## 5️⃣ AI Image Generation

The generated prompt is sent to an image generation model to create a LinkedIn-ready visual.

---

## 7️⃣ Approval Workflow

The workflow supports two publishing methods:

### Option 1

Automatically publish the generated content to LinkedIn.

### Option 2

Send the generated post and image to Gmail for manual approval before publishing.

---

# 📧 Gmail Approval Email

The admin receives an email containing:

- Generated LinkedIn post
- AI-generated image
- Image prompt
- Topic

This allows the content to be reviewed before posting on LinkedIn.

---

# 💼 Use Cases

- Personal Branding
- Content Creators
- Marketing Teams
- Digital Agencies
- Freelancers
- Startup Founders
- AI Automation Services


# 👩‍💻 Author

**Engineer Malaika**


# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

It motivates me to continue building and sharing more AI Automation projects.
