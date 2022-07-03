#Criando cluster de Big Data 
O Hadoop é uma plataforma de software em Java de computação distribuída voltada para clusters e processamento de grandes volumes de dados, vou instalar essa plataforma em um cluster de big data, por isso primeiro vou criá-lo.

O cluster será instalado no Docker


# Hadoop


#### EXERCÍCIOS


Instalação Hadoop

1. Instalação do docker e docker-compose

Docker: https://docs.docker.com/get-docker/ (Links para um site externo.)
Docker-compose: https://docs.docker.com/compose/install/ (Links para um site externo.)

2. Executar os seguintes comandos, para baixar as imagens do Cluster de Big Data:

git clone https://github.com/rodrigo-reboucas/docker-bigdata.git
cd docker-bigdata
docker-compose pull
3. Iniciar o cluster Hadoop através do docker-compose

docker-compose up -d
4. Listas os containers em execução

5. Verificar os logs dos containers do docker-compose em execução

6. Verificar os logs do container namenode

7.  Acessar o container namenode

8. Listar  os diretórios do container namenode

9. Parar os containers do Cluster de Big Data
