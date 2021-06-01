# FastAPI WebSocket Monitoring Dashboard

Real-time server monitoring dashboard built at Idelji (2021-Present). FastAPI backend, WebSocket streaming, Chart.js frontend with dark/light mode.

## My Contributions (Idelji)
- Architected real-time metrics collection system processing server telemetry via WebSocket
- Built responsive dashboard with Chart.js, adopted by 20+ enterprise clients
- Implemented dark/light mode toggle and alerting system for threshold breaches
- Integrated with AWS monitoring infrastructure for production deployment

## Tech Stack
- Backend: FastAPI, Python, WebSocket, Uvicorn
- Frontend: Chart.js, JavaScript, Bootstrap
- Metrics: psutil for system monitoring
- Deployment: Docker, AWS

## Features
- Real-time CPU, memory, disk usage monitoring
- WebSocket-based live data streaming
- Dark/light theme toggle
- Interactive charts with Chart.js
- Alert system for performance thresholds

## Quick Start
```bash
pip install -r requirements.txt
python monitor_agent.py
uvicorn main:app --reload