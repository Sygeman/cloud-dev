# cloud-dev
VS Code with Rancher

- get cx21 rancher
- connect via ssh
- intall docker via https://github.com/docker/docker-install
    curl -fsSL https://get.docker.com -o get-docker.sh
    sh get-docker.sh
- intall docker-compose
    sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
- make docker-compose.yml
- make ssl folder
- make cert.pem key.pem cacerts.pem files in ssl folder
- run
    docker-compose up -d
