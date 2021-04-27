### BootCampo Kubernetes do Kubedev.io Abril/2021


# Principais comandos:

- docker info
- docker version
- docker images
- docker search (parametro)
- docker pull (parametro)
- docker run (nome da imagem)
- docker ps -a
- docker stats (id ou apelido do container)
- docker rmi (nome da imagem)

Algumas flags que podemos utilizar com ele:

    -i permite interagir com o container
    -t associa o seu terminal ao terminal do container
    -it é apenas uma forma reduzida de escrever -i -t
    --name algum-nome permite atribuir um nome ao container em execução
    -p 8080:80 mapeia a porta 80 do container para a porta 8080 do host
    -d executa o container em background
    -v /pasta/host:/pasta/container cria um volume '/pasta/container' dentro do container com o conteúdo da pasta '/pasta/host' do host

Mapeamento de Portas

-p host:container

ex: docker run -it -p 8080:80 nginx
