# Repositório contendo exemplos de projetos em docker  
## add usuário global no linux  
sudo usermod -aG docker $USER  
docker service start  
## comandos  
<a href="https://stack.desenvolvedor.expert/appendix/docker/comandos.html" target="_blank">Comandos básicos<a>  

#### Nome e tag em imagens  
docker build -t imagemteste:tagteste .  
#### -t Rodar pelo interativo  
docker run -t  
#### rmi remove imagens  
#### docker system prune  
#### docker cp (para copiar arquivos)  