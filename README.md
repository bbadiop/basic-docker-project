## DockerHub

### Construire l’image :
docker build -t basic-python-http .

### Taguer l’image :
docker tag basic-python-http monuser/basic-python-http:latest

### Se connecter :
docker login

### Pousser l’image :
docker push monuser/basic-python-http:latest
