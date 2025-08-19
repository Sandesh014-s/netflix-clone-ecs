# Netflix Clone – AWS ECS/ECR/ALB Deployment

This is a simple Netflix-like landing page, containerized with Docker, and deployable on AWS ECS behind an Application Load Balancer.

## Run Locally
```bash
docker build -t netflix:v1 .
docker run -p 80:80 netflix:v1
```
Then open `http://localhost` in your browser.
