# Conversão temperatura
> Repositório dedicado ao Desafio 1 da **Iniciativa Kubernetes**
---
## Instruções
```
# Clone o repositório
git clone https://github.com/CarlosSMA/conversao-temperatura
cd ./conversao-temperatura

# Construa a imagem
docker image build -t {Nome_Usuario}/conversao-temperatura:1.0 .

# Rode o container
docker container run --name aplicacao_node {Nome_Usuario}/conversao-temperatura:1.0

# Verifique o IP com:
docker container inspect aplicacao_node

# Acesse a aplicação pela porta 8080
```
