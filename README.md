# cloud-dev
VS Code with Rancher

- Get cx21 rancher
- Connect via ssh
- Intall docker via https://github.com/docker/docker-install
    curl -fsSL https://get.docker.com -o get-docker.sh
    sh get-docker.sh
- Intall docker-compose
    sudo curl -L "https://github.com/docker/compose/releases/download/1.28.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    sudo chmod +x /usr/local/bin/docker-compose
- Create docker-compose.yml
- Create ssl folder
- Create cert.pem key.pem cacerts.pem files in ssl folder
- Run
    docker-compose up -d

- Get CPX41 (Cluster)
- Connect via ssh
- Intall docker via https://github.com/docker/docker-install
    curl -fsSL https://get.docker.com -o get-docker.sh
    sh get-docker.sh
- Install packages for Longhorn
    apt-get install open-iscsi nfs-common

- Open Ranhcer ranhcer.site.com
- Click Add cluster
- Select Create a new Kubernetes cluster - Existing nodes
- Type some name - sandbox and click next
- Step 1: Select all roles
- Step 2: Paste code to Cluster

- Select sandbox in rancher menu and click Cluster Explorer
- Click Apps & Marketpalce, find and install Longhorn
