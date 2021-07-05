# Jenkins-k8s-permanent-agent
Helm chart for creating Jenkins agents(nodes) running in the k8s cluster via JNLP4 protocol.

To apply run `helm upgrade --install jenkins-permanent-agent --values values.yaml -n default .`