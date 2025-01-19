# kubernetes-setup


Set up the repository
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

Install Yum-utils Package
  yum install yum-utils -y

  
Install Docker Engine
sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin


Start Docker Service 
sudo systemctl start docker

Enable Docker Service
sudo systemctl enable docker 


