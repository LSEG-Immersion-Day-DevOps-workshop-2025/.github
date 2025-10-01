# Welcome to the LSEG Immersion Day: DevOps Workshop 2025! 👋

This GitHub organization houses all the repositories, code samples, and documentation for our hands-on DevOps workshop. We're thrilled to have you here and can't wait to dive into the world of modern software development and operations.

![LSEG DevOps](https://img.shields.io/badge/LSEG-DevOps%20Workshop%202025-blue.svg)

## 🚀 Workshop Overview

This workshop is designed to give you a practical introduction to the core principles and practices of DevOps. Our goal is to bridge the gap between development and operations, demonstrating how a collaborative culture, combined with automation and the right tools, can lead to faster, more reliable software delivery.

Throughout the day, you'll work with the **Trip Planner** application and learn how to:
* **Version Control** with Git and GitHub.
* **Containerize** applications using Docker.
* **Automate** builds and tests with reusable CI/CD pipelines using GitHub Actions.

***

## 🛠️ Prerequisites

To ensure you have a smooth experience, please make sure you have the following installed on your machine **before** the workshop begins:

* **Git:** The distributed version control system. You can download it from [git-scm.com](https://git-scm.com/).
* **Docker Desktop:** An application for building and sharing containerized applications. Download it from [docker.com](https://www.docker.com/products/docker-desktop/).
* **A GitHub Account:** If you don't have one, you can sign up for free at [github.com](https://github.com/).
* **A Code Editor:** We recommend [Visual Studio Code](https://code.visualstudio.com/), but feel free to use your favorite editor.

***

## 📂 Repositories

This organization is structured to mimic a real-world microservices project. Here are the key repositories we'll be using:

* `actions`: This repository contains pre-defined, **reusable GitHub Actions workflows**. We'll use these shared actions to build, test, and deploy our applications, promoting consistency and reducing boilerplate code.
* `trip-planner-frontend`: The source code for the **frontend** of our 'Trip Planner' application. You will clone this repository to implement a CI/CD pipeline using the workflows from the `actions` repo.
* `trip-planner-backend`: The source code for the **backend API** of our 'Trip Planner' application. You will also configure a CI/CD pipeline for this service.

***

## 🗺️ Getting Started

1.  **Fork the application repositories:** Go to the `trip-planner-frontend` and `trip-planner-backend` repositories and click the "Fork" button on the top right. This will create a personal copy of each repository under your own GitHub account.

2.  **Clone your forked repository:** Open your terminal and clone your forked version of the frontend to your local machine. Replace `<your-github-username>` with your actual username.
    ```bash
    git clone [https://github.com/](https://github.com/)<your-github-username>/trip-planner-frontend.git
    ```

3.  **Navigate to the directory:**
    ```bash
    cd trip-planner-frontend
    ```

4.  **Follow the instructions:** Open the `README.md` file within the repository to begin the first exercise. You will repeat these steps for the `trip-planner-backend` repository later in the workshop.

***

## ❓ Getting Help

If you get stuck, have a question, or just want to discuss a concept further, please don't hesitate to:

* **Ask an instructor:** We're here to help! Raise your hand or send a message in the chat.
* **Create an Issue:** If you find a bug or have a suggestion for improving the workshop materials, feel free to open an issue in the main `workshop-guides` repository.

We hope you have a fantastic and educational day. Let's start building!
