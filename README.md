# Criando cluster de Big Data 


O Hadoop é uma plataforma de software em Java de computação distribuída voltada para clusters e processamento de grandes volumes de dados, vou instalar o Hadoop em um cluster de big data, primeiro será instalado o Docker Desktop nos links abaixo. Em seguida o cluster será configurado para finalmente poder trabalhar com o Hadoop.

Link para instalação do Docker Desktop no Windows
https://hub.docker.com/editions/community/docker-ce-desktop-windows/ 

Download WSL 2
https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi


Com o Docker e WSL instalados acessei o terminal de linha de comando Ubuntu. O conteúdo do cluster é uma cortesia da Semantix Academy disponibilizado exclusivamente para fins academicos. Ao acessar o Ubuntu criei a pasta treinamentos através do comando "mkdir treinamentos", em seguida acessei a pasta treinamentos através do comando "cd treinamentos". Dentro da pasta copiei os dados através do comando git clone:


![image](https://user-images.githubusercontent.com/78691172/177059150-89a32948-5cd3-415f-9cbd-c395a80412ed.png)


No clustes identificamos uma pasta através do comando ls:
![image](https://user-images.githubusercontent.com/78691172/177059319-ec94a8c4-bed8-41a6-bfc0-d0a3555b8a34.png)



Acessei essa pasta e baixei as imagens do Docker Compose através do comando Docker-compose pull



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
