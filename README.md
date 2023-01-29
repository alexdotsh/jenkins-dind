docker buildx build --platform linux/amd64 --tag dind-client-jenkins-agent .
docker tag dind-client-jenkins-agent alexdotsh/dind-client-jenkins-agent
docker push alexdotsh/dind-client-jenkins-agent
