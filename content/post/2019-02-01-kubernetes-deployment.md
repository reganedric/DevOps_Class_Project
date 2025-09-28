---
title: First Kubernetes Deployment
date: 2019-02-01
tags: ["kubernetes", "code"]
---

# First Kubernetes Deployment

First application on Kubernetes using Kubernetes deployments

<!--more-->

## Deploy the Application

Jalankan aplikasi pertama di Kubernetes dengan perintah berikut:

```sh
kubectl run kubernetes-bootcamp \
  --image=gcr.io/google-samples/kubernetes-bootcamp:v1 \
  --port=8080
