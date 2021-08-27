# docker
Estudos envolvendo docker
comandos aprendido
- `docker ps`: pra listar os containers em execução
- `docker ps -a`: pr: a listar todos os containers
- `docker run -it nome_da_imagem`: pra conectar o terminal a imagem
- `docker start ID`: inicializa um container
- `docker stop ID`: para um container
- `docker start -a -i ID`: inicia o container com id e integra oterminal alem de permitir interação
- `docker rm ID`: Remove o container
- `docker container prune`: Remove todos os containers parados
- `docker rmi nome_da_imagem`: Remove a imagem
- `docker run -d -P --name Nome nomeimagem`: executa um container, não trava o terminal nele  e cirar uma porta
- `docker run -d -p 12345:80 nomeimagem`: defina a porta
- `docker run -d -P -e AUTHOR="Fulano" nomeimagem`: define variavel de ambiente
