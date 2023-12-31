# [TechVibes](https://angular-tech-vibes-blog.vercel.app/) - Blog sobre tecnologia desenvolvido com Angular  (Em Desenvolvimento)

Bem-vindo ao nosso projeto em desenvolvimento, focado em trazer conteúdo de alta qualidade sobre o fascinante mundo da tecnologia utilizando Angular. Estamos empenhados em criar uma plataforma dedicada a fornecer informações relevantes e envolventes sobre os avanços tecnológicos. Este blog abrangerá uma ampla gama de tópicos, desde as últimas notícias até análises aprofundadas, histórias de destaque e muito mais.

## Recursos Planejados

- **Notícias Tecnológicas:** Diárias e atualizadas.
- **Artigos Detalhados:** Análises aprofundadas sobre eventos e desenvolvimentos tecnológicos.
- **Cobertura Abrangente:** Diversos temas, desde inteligência artificial e computação em nuvem até inovações em dispositivos eletrônicos.
- **Interface de Usuário Responsiva:** Garantindo uma experiência de leitura agradável.

Estamos entusiasmados com o desenvolvimento deste projeto e ansiosos para compartilhar com você as últimas novidades e insights do universo tecnológico. Agradecemos pela sua visita e apoio contínuo.


## Como Executar o Projeto Localmente

Para executar o projeto localmente, siga estas etapas:

1. Instale o Angular CLI.
2. Clone o repositório do projeto.
3. Navegue até o diretório do projeto.
4. Execute o comando `ng serve`.

## Instalando o Angular CLI

Para instalar o Angular CLI, execute o seguinte comando em seu terminal:

    npm install -g @angular/cli

**Clonando o repositório do projeto**

Para clonar o repositório do projeto, execute o seguinte comando em seu terminal:

    git clone https://github.com/higorsilva97/angular-tech-vibes-blog.git

**Navegando até o diretório do projeto**

Após clonar o repositório, navegue até o diretório do projeto:

    cd angular-tech-vibes-blog.git


## Consumo da News API

Este projeto consome a [News API](https://newsapi.org/) para fornecer notícias tecnológicas atualizadas. No entanto, em ambiente de produção a API é restrita, pode ser necessário utilizar um mock de dados em vez da News API. Neste projeto, optamos por usar o mock em produção por esse motivo.:

1. **Obtenha uma Chave da API da News API:**
   - Acesse [News API](https://newsapi.org/) e registre-se para obter uma chave de API gratuita.
   - Copie sua chave de API.

2. **Configure a Chave da API no Projeto:**
   - No diretório do projeto, procure o arquivo de configuração relacionado à News API.
   - Adicione sua chave de API no local apropriado.

### Utilizando o Mock de Dados em Produção

Na fase atual de desenvolvimento o aplicativo Angular está configurado para usar um serviço de mock de notícias em vez da News API. Este serviço utiliza um conjunto predefinido de dados simulados para imitar a resposta da News API.

#### Instruções para Configuração

1. Abra o arquivo `src/app/services/news-mock.service.ts` para visualizar o serviço de mock.

2. O mock atualmente retorna um conjunto de dados fixo, simulando respostas da News API. Você pode ajustar os dados conforme necessário para testar diferentes cenários.

3. Mock Data `src\assets\mock-data.json`

4. Certifique-se de entender as implicações de usar um mock em produção e avalie se atende aos requisitos do seu caso de uso.

3. **Execute o Projeto:**
   - Continue com as instruções de execução do projeto mencionadas anteriormente.
  

**Executando o projeto**

Para executar o projeto, execute o seguinte comando em seu terminal:

    ng serve


Isso irá iniciar um servidor local na porta 4200. Você pode acessar o projeto em seu navegador no seguinte endereço:

    http://localhost:4200


**Parando o projeto**

Para parar o projeto, pressione `Ctrl`+`C` no terminal.

## Contribuições

Se você tiver interesse em contribuir com o projeto, por favor, envie seu feedback para higorsilva97@gmail.com ou envie uma solicitação de pull request para o [repositório](https://github.com/higorsilva97/angular-blog/).

## Recursos Adicionais

* [Documentação do Angular](https://angular.io/docs)
* [Tutoriais do Angular](https://angular.io/tutorial)
* [Exemplos do Angular](https://angular.io/examples)

## Atualizações

* O projeto está atualmente em desenvolvimento e novas funcionalidades serão adicionadas regularmente.



