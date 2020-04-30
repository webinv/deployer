FROM alpine:3

RUN \
    apk add --update --no-cache curl openssl ca-certificates python py-pip bash && \
    curl -o /usr/local/bin/kubectl https://storage.googleapis.com/kubernetes-release/release/v1.18.0/bin/linux/amd64/kubectl && chmod +x /usr/local/bin/kubectl && \
    curl https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash && \
    mkdir $HOME/.kube