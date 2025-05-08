# wordpress-deployment
# Project Overview
This repository contains Kubernetes manifests to deploy a WordPress site with the following features:

Persistent storage for WordPress data

Secure management of sensitive information using Kubernetes Secrets

Scalable architecture
# Deployment Components
Persistent Volume (PV) and Persistent Volume Claim (PVC)

Ensures data persistence for WordPress

Retains data even if pods are restarted or rescheduled

Secrets

Securely stores sensitive information (database credentials)

Prevents hardcoding of passwords in configuration files

MySQL Deployment

Database backend for WordPress

Uses persistent storage

WordPress Deployment

Frontend web application

Connects to MySQL database
