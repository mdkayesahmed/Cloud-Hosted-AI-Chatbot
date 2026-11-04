# Cloud-Hosted-AI-Chatbot
Deployment of an AI chatbot using Google Cloud, Ollama, Docker and Open WebUI

## Project Overview

This project demonstrates the deployment of an AI chatbot using Google Cloud Platform (GCP), Ollama, Docker, and Open WebUI.

The chatbot runs on a Google Cloud virtual machine and provides a browser-based interface for interacting with a locally deployed large language model.

## Technologies Used

* **Google Cloud Platform:** Cloud infrastructure and virtual machine hosting.
* **Ubuntu 22.04:** Operating system for the virtual machine.
* **Ollama:** Runs the AI language model.
* **Llama 3 8B:** Language model used for chatbot responses.
* **Docker:** Containerisation platform used to deploy Open WebUI.
* **Open WebUI:** Browser-based interface for interacting with the chatbot.

## Project Architecture

```text
User Browser
     |
     v
Google Cloud Firewall
     |
     v
Google Cloud VM (Ubuntu)
     |
     v
Docker Container (Open WebUI)
     |
     v
Ollama + Llama 3 Model
```

## Implementation

### Phase 1 — Google Cloud Setup

Created and configured a Google Cloud virtual machine running Ubuntu.

### Phase 2 — Ollama Installation

Installed Ollama, downloaded the Llama language model, and tested chatbot responses through the command-line interface.

### Phase 3 — Open WebUI Deployment

Deployed Open WebUI using Docker to provide a graphical interface for interacting with the chatbot.

### Phase 4 — Firewall Configuration

Configured Google Cloud firewall access to allow authorised browser connections to Open WebUI.

### Phase 5 — Testing

Verified the chatbot through both command-line and browser-based testing.

## Project Documentation

The repository contains:

* Assessment report
* Deployment commands and configuration notes
* Screenshots of the implementation
* Chatbot testing evidence

## Academic Information

**Unit:** NIT2113 — Cloud Application Development

**Project:** AI Chatbot Deployment Using Google Cloud

## Note

The chatbot requires a running Google Cloud virtual machine. This GitHub repository contains the project documentation and deployment information, not a continuously hosted chatbot.

