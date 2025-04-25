# ConvoyControl [COMING SOON]

<!-- ![alt text](logo.png =100x50) -->
<img src="logo.png" width="300" height="300" />

**ConvoyControl** is a real-time fleet management system designed for autonomous trucking companies. It simulates telemetry data ingestion, intelligent job dispatching, and real-time monitoring — all deployed and scaled using Kubernetes.

## Tech Stack
- **Backend**: FastAPI + Redis + Kubernetes
- **Frontend**: React.js with live map visualization
- **Infrastructure**: Docker, Helm, Prometheus, GitHub Actions

## Features
- Real-time truck telemetry collection (location, speed, fuel)
- Redis-backed fast storage and job queueing
- Dynamic job dispatch logic based on truck availability
- Admin dashboard for monitoring and control
- Kubernetes-native deployments with autoscaling

## Microservices
- `telemetry-api`: Receives and stores truck data
- `dispatch-manager`: Assigns jobs and pushes to Redis queues
- `mock-truck`: Simulates autonomous trucks sending data
- `frontend`: Dashboard UI for tracking and dispatch

## 🚀 Setup Instructions
> Coming soon...

## 📍 Live Demo
> Optional: Link to deployed version (K8s + domain)
