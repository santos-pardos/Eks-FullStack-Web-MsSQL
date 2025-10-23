## EKS + App + API + MsSQL  (Docker)

## Install Docker and Docker-Compose - Ubuntu
```
# Add Docker's official GPG key:
sudo apt-get update
sudo apt-get install ca-certificates curl
sudo install -m 0755 -d /etc/apt/keyrings
sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
sudo chmod a+r /etc/apt/keyrings/docker.asc

# Add the repository to Apt sources:
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
  $(. /etc/os-release && echo "${UBUNTU_CODENAME:-$VERSION_CODENAME}") stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
sudo apt-get update
```

```
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
sudo systemctl start docker
sudo systemctl enable docker
docker-compose --version
```

```
sudo groupadd docker
newgrp docker
sudo apt install docker-compose -y
sudo apt install git -y
sudo apt install unzip -y
```
## AWS CLI
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```


## SQL Server Management Studio (SSMS)
```
https://learn.microsoft.com/es-es/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
```
DBeaver Community 24.3.4  (Portable: Zip file)
```
https://dbeaver.io/download/
```

## Tools
```
docker run --name cloudbeaver --rm -ti -d -p 8080:8978 -v /opt/cloudbeaver/workspace dbeaver/cloudbeaver:latest
```
```
docker run -it  nicolaka/netshoot sh
```
```
kubectl run tmp-shell --rm -i --tty --image nicolaka/netshoot
```
