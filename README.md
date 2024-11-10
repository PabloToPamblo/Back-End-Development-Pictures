# 🎶 Artist Platform: A Real-World DevOps Challenge 🎶

This project is a hands-on exercise designed to simulate a real-world DevOps environment. The objective is to build a platform for artists to upload their songs, schedule concerts, and share photos from past events, allowing fans to explore music, purchase tickets, and view exclusive concert photos. This project uses microservices, multiple deployment platforms, and an Agile workflow to ensure scalability, maintainability, and real-world applicability.

## 🌟 Project Objective
Create a scalable, multi-service platform for artists and fans that includes:
- A **Django**-based web service to manage user accounts, ticketing, and core functionalities.
- Microservices built with **Flask** to handle song and lyrics data, as well as concert images.
- An Agile development workflow with **SCRUM** using **JIRA** for project management.

## 💻 Tech Stack

| Component                   | Technology      | Platform            |
|-----------------------------|-----------------|----------------------|
| **Web Service**             | Django          | Kubernetes          |
| **Songs and Lyrics Service**| Flask + MongoDB | OpenShift           |
| **Concert Images Service**  | Flask + IBM Cloud DB | IBM Cloud Engine |

## 📁 Project Structure

- **Django (Main Web Service)**: Provides the platform's main interface for users, including the ability to browse music, buy tickets, and view concert images. Hosted on a Kubernetes cluster.
- **Flask (Songs and Lyrics Service)**: Handles access to songs and lyrics, deployed on OpenShift with MongoDB as its database.
- **Flask (Concert Images Service)**: Manages concert images, deployed on IBM Cloud Engine with IBM Cloud DB.

## 🗂 Repository Structure

```plaintext
├── artist-platform/
│   ├── django-service/               # Django project for main web service
│   ├── songs-service/                # Flask microservice for songs and lyrics
│   ├── images-service/               # Flask microservice for concert images
│   ├── kubernetes/                   # Kubernetes manifests for deployment
│   ├── openshift/                    # OpenShift configurations
│   ├── ibm-cloud/                    # IBM Cloud Engine configurations
│   └── README.md                     # Project overview and documentation
```
## 🔄 Workflow

To simulate a real-world work environment, this project includes:

- **Git Branch Management**: Code is shared across different branches on GitHub, emulating the workflow of an enterprise project.
- **SCRUM Methodology**: Project timelines are managed using JIRA to simulate an Agile workflow with SCRUM practices.

## 🏆 Goals of This Project

- Apply DevOps best practices for deploying microservices across multiple cloud platforms.
- Simulate a real-world Agile workflow, utilizing SCRUM and project management in JIRA.
- Create a scalable, maintainable system using Django and Flask microservices.

## 💬 Contributing

I'm excited to make this platform a collaborative project! Whether you’re a DevOps enthusiast, Django or Flask developer, or a cloud services pro, your insights can help us make this project even better. Feel free to fork the repo, submit pull requests, or open issues with suggestions and ideas. Let’s make this a real-world DevOps success together!

## 📄 License

This project is open-source and available under the MIT License.
