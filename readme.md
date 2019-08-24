# Steps

- Install Docker for Ubuntu
- sudo curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)"  -o /usr/local/bin/docker-compose
- sudo chmod +x /usr/bin/docker-compose
- sudo chown $USER:docker /var/run/docker.sock
- docker-compose up -d --build
- http://<DOCKER_HOST>:8000