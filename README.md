# GenAI Platform – Canary, SLOs & Reliability Engineering

## Overview
This project demonstrates a **production-grade GenAI / LLM inference platform** on Kubernetes with a strong focus on:
- Reliability
- Safe deployments
- Latency-focused SLOs

## Architecture Flow

Client → Ingress → LLM Pods  
                ↘ Prometheus → Grafana

## Key Concepts
- Canary deployments using Argo Rollouts
- SLO-driven reliability using Prometheus
- Controlled blast radius during model updates

## Folder Structure
- k8s/: Inference and rollout manifests
- slo/: Service Level Objectives

## How to Run
1. Install Argo Rollouts controller
2. Apply inference and rollout YAMLs
3. Monitor metrics via Prometheus & Grafana

## Author
Mahi – SRE / DevOps Engineer
