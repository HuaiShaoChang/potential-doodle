# Docker
## Install
### CentOS 8
```bash=
sudo dnf config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
sudo dnf install -y docker-ce
sudo systemctl enable --now docker
sudo usermod -aG docker username
```
