PROJETO FINAL JAVA

Sistema de Biblioteca

Informações Gerais sobre o Projeto:

Este é um sistema de biblioteca desenvolvido em Java que permite gerenciar livros, usuários e empréstimos de livros. O objetivo do projeto é fornecer uma ferramenta simples para o gerenciamento de uma biblioteca, incluindo cadastro de livros e usuários, busca e edição de dados, e controle de empréstimos e devoluções.

___Funcionalidades Principais___

- Cadastrar Livro: Permite cadastrar novos livros na biblioteca.
- Buscar Livro: Permite buscar livros pelo título.
- Atualizar Dados do Livro: Permite atualizar as informações dos livros cadastrados.
- Apagar Livro: Permite remover livros do sistema.
- Listar Todos os Livros: Exibe todos os livros cadastrados na biblioteca.
- Emprestar Livro: Permite realizar o empréstimo de um livro a um usuário.
- Listar Livros Emprestados: Exibe todos os livros atualmente emprestados.
- Cadastrar Usuário: Permite cadastrar novos usuários no sistema.
- Listar Usuários: Exibe todos os usuários cadastrados na biblioteca.
- Atualizar Dados do Usuário: Permite atualizar as informações dos usuários cadastrados.
- Devolver Livro: Permite registrar a devolução de um livro emprestado.


___Informações sobre as Classes e suas Relações___

---Classes---
- App.java: Classe principal que executa o sistema.
- Autor.java: Classe que representa um autor.
- Biblioteca.java: Classe que gerencia livros, usuários e empréstimos.
- Categoria.java: Classe que representa uma categoria de livro.
- Console.java: Classe utilitária para leitura de dados do console.
- Emprestavel.java: Interface que define métodos para objetos que podem ser emprestados.
- Emprestimo.java: Classe que representa um empréstimo de livro.
- Livro.java: Classe que representa um livro.
- Persistente.java: Interface que define métodos para persistência de dados.
- Sistema.java: Classe que contém a lógica do sistema e interação com o usuário.
- Usuario.java: Classe que representa um usuário.

---Relações entre as Classes---
- **Agregação**: A classe `Biblioteca` agrega as classes `Livro`, `Usuario` e `Emprestimo`, gerenciando a coleção de livros, usuários e empréstimos.
- **Composição**: A classe `Livro` pode ter uma composição com a classe `Autor` e `Categoria`, significando que um livro tem um autor e uma categoria.
- **Associação**: A classe `Emprestimo` associa a classe `Livro` e a classe `Usuario`, indicando quais livros estão emprestados para quais usuários.


___Como Executar o Projeto___

---Pré-requisitos---
- Java Development Kit (JDK) 8 ou superior
- Um ambiente de desenvolvimento Java, como Eclipse ou IntelliJ IDEA, etc.


___Instruções de Execução___

1. Clone o repositório para sua máquina local:
    ```
    git clone <URL_DO_REPOSITORIO>
    
    ```

2. Navegue até o diretório do projeto:
    ```
    cd sistema-biblioteca
    
    ```

3. Compile o projeto:
    ```
    javac *.java
    
    ```

4. Execute a aplicação:
    ```
    java App
    
    ```


___Uso do ChatGPT___

O ChatGPT foi utilizado no desenvolvimento do projeto para:
- Auxiliar na criação de estruturas de classes e interfaces.
- Fornecer explicações detalhadas sobre conceitos de programação orientada a objetos.
- Sugerir melhorias e otimizações no código.
- Auxiliar na documentação do projeto, incluindo a criação deste README.


___Referências e Recursos___

- [Documentação Oficial do Java](https://docs.oracle.com/javase/8/docs/)
- [Chat GPT](https://chatgpt.com/)
- [GitHub - Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- Materiais didáticos utilizados no curso.
