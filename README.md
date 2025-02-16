# Repository Index

## Overview
Welcome to the App-Deploymet-on-Kubernetes-Cluster Porject! This repository contains the projects, scripts, and documentation organized into distinct directories.
That were done by me while pursuing my DevOps Course.

This `README.md` provides an index of all key components of the repository to help you navigate and understand the contents.

> IMPORTANT NOTE

> We have a product called V-Profile. It is a website written in Java. Consists of multiple services.
> We will be deploying this product on virtual machines and cloud platforms using differnt services.
> The same code or the product has been used for all the projects but with the different approaches based on the differnt use cases.

> NOTE: The code is not written/developed by me, this code is from my instructor who has designed this code for the differnet scenarios.


## Directory Structure

The repository is organized as follows:

```plaintext
├── Architecture/
├── Docker-Files/
├── kubedefs/
├── src/
├── About_the_Project.md/
├── docker-compose.yml/
├── pom.xml/
├── LICENSE/
└── README.md
```

## (App-Deploymet-on-Kubernetes-Cluster)
In this project we are going to use our Java vprofile application which we have Containerized and we're going to run it on Kubernetes Cluster for production.
So we need a Kubernetes cluster and we are going to use Kops to launch my Kubernetes cluster.
We also need Containerized application. We are going to use a vprofile. We have already done a project on containerizing our vprofile application.
So these are two main requirements.
We need a Kubernetes cluster and we need Containerized application.

Then we are going to write Kubernetes definition files to create our objects on kubernetes cluster, we're going to use deployment service secret and volume.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


