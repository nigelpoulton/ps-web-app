# Test app for demonstrating containerizing web app

Super-simple Node web app for containerization demos

## Instructions for use

1. Fork the repo 
2. Clone fork locally
3. Build Docker iamge `docker image build -t <tag> .` from within the root directory of the repo 
4. Push image to container registry
5. Run container/Pod using the created image (K8s YML file provided 'web-test.yml')