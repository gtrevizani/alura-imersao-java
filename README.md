# Imersão Java - Alura
> Por Guilherme Iglesias Trevizani <guilhermetrevz@outlook.com>
>
> Técnico em Desenvolvimento de Sistemas
>
> Desenvolvedor Java
<hr>

Repositório para estudo construído com base no treinamento intensivo em desenvolvimento back-end com a linguagem Java proposto pela plataforma alura.
Imersão finalizada com sucesso, todas as aulas ao vivo foram concluídas e muitas experiência foi absorvida.

# AULA 1: CONSUMINDO UMA API DE FILMES COM JAVA

Construir um aplicação para consumir a API do [IMDb](https://www.imdb.com/) e exibir os filmes mais populares, destacando seus pôsteres e visualizando sua classificação, sem utilização de biblioteca externa.

**Links úteis:**

- Documentação da classe [HttpRequest do pacote java.net.http](https://docs.oracle.com/en/java/javase/17/docs/api/java.net.http/java/net/http/HttpRequest.html).
- Documentação da API do IMDb: [https://imdb-api.com/api](https://imdb-api.com/api)

Devido a instabilidade no site do IMDb, consumi via JSON -   [https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/TopMovies.json](https://raw.githubusercontent.com/alura-cursos/imersao-java-2-api/main/TopMovies.json)

# AULA 2: GERANDO FIGURINHAS PARA WHATSAPP

Criar um gerador de figurinhas explorando outras bibliotecas nativas do Java, para que possamos enviar por Whatsapp os nossos filmes preferidos.

**Links úteis:**

- Documentação do [pacote javax.imageio](https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/javax/imageio/package-summary.html), que trata de leitura e escrita de imagens.
- Documentação da [classe BufferedImage](https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/java/awt/image/BufferedImage.html), que representa uma imagem no Java
- Documentação da classe [Graphics2D](https://docs.oracle.com/en/java/javase/17/docs/api/java.desktop/java/awt/Graphics2D.html), a “caneta” que permite escrever, desenhar e imprimir outras imagens em uma imagem original.
- Documentação da [abstração InputStream](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/io/InputStream.html), que representa um fluxo de leitura de dados de qualquer fonte, como arquivos, URLs, entre outros.

# AULA 3: LIGANDO AS PONTAS, REFATORAÇÃO E ORIENTAÇÃO A OBJETOS

Chegou o momento de melhorar o código com as refatorações necessárias para torná-lo mais flexível e fácil de entender. Foram empregadas práticas de refatoração de código e orientação a objetos, com a utilização injeção de dependências e aprimoramento de coesão das classes. Também foram criadas camadas de serviço com clientes HTTP, extratores de dados e geradores, bem como os pacotes de parser e entidades.

# AULA 4: CRIANDO NOSSA PRÓPRIA API COM SPRING 
     
Nessa aula o objetivo é construir uma API REST para expor nosso próprio conteúdo, utilizando ferramentas profissionais como o Spring Framework e um banco de dados NoSQL.

**Ferramentas utilizadas:**

| Framework  | Link   | Banco de Dados | Link   | Plataforma API | Link    |
| :-----:    | :-----:| :-----:        | :-----:| :-----:        | :-----: |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original-wordmark.svg" width="40" height="40" /> | [Spring  Boot](https://spring.io/) | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" width="40" height="40" /> | [MongoDB](https://www.mongodb.com/) | <img src="https://user-images.githubusercontent.com/7853266/44114706-9c72dd08-9fd1-11e8-8d9d-6d9d651c75ad.png" width="40" height="40" /> | [Postman](https://www.postman.com/)


# AULA 5: PUBLICANDO A API NO CLOUD

Tornar a aplicação acessível por qualquer pessoa, fazendo o deploy na nuvem. Além disso, vamos gerar figurinhas a partir do conteúdo dessa nossa API.

**Ferramentas utilizadas:**

| Containers | Link   | PaaS    | Link   | 
| :-----:    | :-----:| :-----: | :-----:|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" height="40" /> | [Docker](https://www.docker.com/) | <img src="https://fly.io/static/images/brand/logo-landscape.svg" width="40" height="40" /> | [Fly.io](https://fly.io/) |

---

### INSTRUTORES

|<img src="https://github.com/brunoesm07/imersao-java-2023/blob/a9e877af39c60864d9dbaf894b2ce09c3ebd9ca2/Consumindo-uma-API-com-Java/assets/Paulo.png" width="160" height="160" /> | <img src="https://github.com/brunoesm07/imersao-java-2023/blob/a9e877af39c60864d9dbaf894b2ce09c3ebd9ca2/Consumindo-uma-API-com-Java/assets/jacqueline.png" width="160" height="160" /> | <img src="https://github.com/brunoesm07/imersao-java-2023/blob/a9e877af39c60864d9dbaf894b2ce09c3ebd9ca2/Consumindo-uma-API-com-Java/assets/alexandre.png" width="160" height="160" /> | 
| :-----: | :-----: | :-----: |
| Paulo Silveira | [Jacqueline Oliveira](https://github.com/jacqueline-oliveira)| [Alexandre Aquiles](https://github.com/alexandreaquiles) |
