# Test app for containerizing web app

Super-simple Node web app for containerization demos in Pluralsight video courses.

## Instructions for use

1. Fork the repo 
2. Clone fork locally
3. Build Docker iamge `docker image build -t <tag> .` from within the root directory of the repo 
4. Push image to container registry
5. Run container/Pod using the created image 

## Pre-created image

A publically available pre-created iamge is available for download [here](https://hub.docker.com/repository/docker/nigelpoulton/ps-web)
