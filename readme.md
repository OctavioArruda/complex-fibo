# Really complex fibonacci calcutor with React!
- Multiple Services Docker setup

## Tools
- Docker
- Redis
- Nginx
  - Api gateway 
  - App routing
- Postgres
- Node
  - Express
- React
- AWS Elastic Beanstalk
- AWS ElastiCache Redis
- AWS RDS

### Docker usage
- `docker build -f Dockerfile.dev .`
  - `f` flag stands for a specific file name
  - the period means: "use current directory"
- `docker tag b981b4fccd6e octavio/complex-dev:latest`
- tagging the generate image