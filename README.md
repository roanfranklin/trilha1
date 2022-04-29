[ Diretorio Base - Repositório ]

your_repo
   + app
      + app.py
   + README.md
   + .gitignore
   + .dockerignore
   + Dockerfile_ubuntu
   + Dockerfile_python 
   + docker_compose.yml
   + requirements.txt


[ Tarefa ]

1º criar um Dockerfile usando a imagem base do:
- python
- ubuntu

2º build as duas imagens

3º levantar 2 container com a mesma aplicação, usando cada imagem "buildada":
- imagem 1 levantar na porta 8080
- imagem 2 levantar na porta 9090

4º criar um docker-compose para levantar buildar a imagem e levantar em suas respectivas portas!

5º build 2x imagens pelo github actions.

6º push das 2x imagens para o dockerhub

OBS.: Fazendo esse 6 passos aí, já tem o entendimento básico para fazer uma parte do teste para Analisa Junior DevOps!

7º README de como executar/run no dockerhub!

OBS.: Esse procedimento é para uso localmente!

8º Construir um ambiente Cloud - Kubernetes usando o Terraform.

OBS.: O Ambiente criado em terraform pode conter:
      - s3
      - route53
      - k8s (contem ingressroute, kong, traefik, ou outro)

9º Construir os manifestos k8s para cada aplicação.

10º Atualizar a pipline para aplicar um novo deployment da apalicação.

OBS.: Já dá pra fazer o teste para Analisa Junior nível 1 e já está muito próximo de Analista Junior 2 DevOps!
