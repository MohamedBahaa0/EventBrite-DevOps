# EventBrite DevOps

DevOps automation for an Eventbrite-like event management platform: CI/CD with Jenkins, containerized services with Docker, Nginx as reverse proxy, and Prometheus-based monitoring on Linux / AWS.

I owned the DevOps side of the project.

## What's here

| Folder | Contents |
|---|---|
| `scripts/Jenkins` | Jenkins pipeline scripts for build, test and deploy |
| `scripts/Docker` | Dockerfiles and container configuration |
| `scripts/nginx` | Nginx reverse proxy configuration |

## Highlights

- Automated build → test → deploy pipeline with Jenkins
- Containerized services with Docker, deployed to AWS, traffic routed through Nginx
- systemd unit files to keep services running and restart them on failure
- Monitoring with Prometheus, node-exporter and Grafana, plus centralized logs for faster debugging
- Linux server administration and a Postfix mail server for transactional emails

## Tech stack

Jenkins · Docker · Nginx · AWS · Linux · systemd · Prometheus · node-exporter · Grafana · Postfix

## Links

- Documentation: https://bahaa.gitbook.io/devops/
