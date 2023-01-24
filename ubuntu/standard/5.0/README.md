# Build

docker build . -t alexeypolitovcct/aws-codebuild-node16-lastools201

## M1

docker build --platform linux/amd64 . -t alexeypolitovcct/aws-codebuild-node16-lastools201


# Debug Run

docker run -d -t alexeypolitovcct/aws-codebuild-node16-lastools201

## M1

docker run --platform linux/amd64 -d -t alexeypolitovcct/aws-codebuild-node16-lastools201


# Docker Hub

docker push alexeypolitovcct/aws-codebuild-node16-lastools201