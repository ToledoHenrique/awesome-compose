# Membros do Grupo: Bruno Ian, Carlos Piva, Henrique Toledo e Leonardo Moresco.

# Awesome Compose

## Vamos começaer

Estas instruções irão ajudá-lo na fase inicial de criação e
implantando amostras de aplicativos em contêineres com o Docker Compose.

### Pré-requisitos

- Certifique-se de ter o Docker e o Docker Compose instalados
  - Windows ou macOS:
    [Instale o Docker Desktop](https://www.docker.com/get-started)
  - Linux: [Install Docker](https://www.docker.com/get-started) and then
    [Docker Compose](https://github.com/docker/compose)
- Baixe as amostras deste repositório.

### Executando uma amostra

O diretório raiz de cada amostra contém o `compose.yaml` que
descreve a configuração dos componentes de serviço. Todas as amostras podem ser executadas em
um ambiente local entrando no diretório raiz de cada um e executando:

```console
docker compose up -d
```

Verifique o `README.md` de cada amostra para obter mais detalhes sobre a estrutura e
Qual é o resultado esperado.
Para parar e remover todos os contêineres do aplicativo de amostra, execute:

```console
docker compose down
```

### Guias de início rápido

Além de todas as amostras prontas para execução do Compose listadas acima da pasta [official-documentation-samples](official-documentation-samples/README.md) contém guias de início rápido. Cada um desses guias passo a passo explica quais arquivos precisam ser criados para criar e executar um aplicativo Docker Compose.

<!--lint disable awesome-toc-->
## Contribuir

Congratulamo-nos com exemplos que ajudam as pessoas a entender como usar o Docker Compose para
aplicações comuns. Verifica a [Contribution Guide](CONTRIBUTING.md) para mais detalhes.

link do repositório original: https://github.com/docker/awesome-compose
