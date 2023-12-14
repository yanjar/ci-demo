FROM nginx:1.25.3
COPY secret.yaml /secret.yaml
WORKDIR /home/se/.aws/
COPY awssecret.json credentials.json
COPY awssecret.txt credentials.txt