<style>
  h1 {
    text-align: center;
  }
</style>

# GCP GKE Demo

## Contents

1. [Definition](#definition)
2. [Technologies](#technologies)
3. [Folder structure](#folder-structure)

## Definition

The main goal of this project is to define the complete architecture of an application ready for production that uses Google technologies for cloud, Kubernetes and database.

> *This project can be used as an example to create similar ones or as a good starter point to learn GCP based architectures.*

## Technologies

Microservices:
- `Python`: High-level programming language defined to create the microservices.
- `⁠FastAPI`: Python web-based framework to easily create API REST services.
- `Firebase`: Google service to define a fully managed backend infrastructure. We're just gonna use it as a database for this project.

Frontend:
- `Astro`: Web framework to create modern scalable applications.
- `TypeScript`: The typed version of JavaScript. Programming languaje to work with the web.
- `⁠TailwindCSS`: CSS Framework to apply easily utility classes.

Infrastructure:
- `GCP`: Google Cloud Platform. Cloud provider we're gonna use for the project.
- `GKE`: Google Kubernetes Engine. The engine to work with Kubernetes within GCP.
- `⁠Docker`: Platform to create and define containers. 
- `Terraform`: IaaC tool to define your physical infrastructure with code.
- ⁠`Github Actions`: Standalone commands to create a job based on events defined by the developer.

## Folder structure

- `backend`: Set of folders that define separated microservices for the project.
  - `auth`: Microservice dedicated to authentication & authorization.
  - `todos` Microservice dedicated to manage todo data & operations. 
- `frontend`: Astro application to define the client view of the project.
- `infrastructure`: Set of IaaC files to define the physical architecture of the project.
