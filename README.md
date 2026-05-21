# Node.js Application Deployment

## Tech Used
- Node.js
- Docker
- GitHub
- AWS EC2

## Run Project

Build Image:
```bash
docker build -t node-app .
```

Run Container:
```bash
docker run -d -p 3000:3000 node-app
```

## Access
http://EC2-IP:3000
