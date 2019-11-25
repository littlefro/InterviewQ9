1. Created docker image
2. Logged into docker.io via "docker login -u <username> -p <pass> docker.io"
3. Created a tag for my image via "docker tag python-interview <username>/python-interview:v1"
4. Pushed docker image up to docker.io "push <username>/python-interview:v1"
5. Created interview-pod.yaml
6. Used kubectl version to see if it's installed
7. Created a Pod based on yaml via "kubectl apply -f interview-pod.yaml"
8. Looked for created pod "get pods"
9. Checked log/output via "kubectl logs interviewq"