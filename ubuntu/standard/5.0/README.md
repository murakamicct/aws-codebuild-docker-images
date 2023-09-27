# Build

docker build . -t murakamicct/aws-codebuild-node20-pointcloud -m 4g

## M1

docker build --platform linux/amd64 . -t murakamicct/aws-codebuild-node20-pointcloud


# Debug Run

docker run -d -t murakamicct/aws-codebuild-node20-pointcloud

## M1

docker run --platform linux/amd64 -d -t murakamicct/aws-codebuild-node20-pointcloud


# Docker Hub

docker push murakamicct/aws-codebuild-node20-pointcloud