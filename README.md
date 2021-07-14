
# TREINAMENTO PSG - WMALDONADO

## CRUD-JAVA-WEB-POO-BD

Projeto: Cadastro de Login com persistencia de dados no Mysql

CRUD:

- Java Web
- Maven
- JSP
- SQL
- JDBC
- JUnit
- Materialize

## Sistema suportados:
### Windows, Linux e MacOS

### Requisitos:
- Baixe o [Java 8](https://www.java.com/pt_BR/download/).
- Baixe o [Eclipse IDE](https://www.eclipse.org/downloads/).
- Baixe o [Tomcat 8.5](https://tomcat.apache.org/download-80.cgi).
- Baixe o [MySQL](https://dev.mysql.com/downloads/workbench/).

### Configuração e instalação
- Java
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Não ha necessidade
- Eclipse
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Com o Eclipse iniciado, vá em:
      - "File"
        - "Open Projects from File System"
          - Selecione o diretório que você baixou o repositório da aplicação e clique em "finish".
    - Clique no botão direito na pasta do projeto
      - Vá em "Servers" (se encontra na parte inferior do programa, caso não tenha encontrado, procure por ele em "Quick Acess")
        - Clique para adicionar um novo servidor
          - Selecione "Tomcat v8.5 Server" e clique em Next
            - Selecione a pasta em que você baixou o "Tomcat 8.5"
            - Selecione o JRE como: jre_1.8.0_xxx e clique em "Finish"
- MySQL
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Configure a porta do MySQL como padrão (3306)
    
### Uso da aplicação
Com o Eclipse rodando e o projeto selecionado, espere que o Maven baixe todas as dependências do projeto, logo após, verifique se o SQL está rodando na porta 3306
- Baixe e execute o Script SQL: [crud_java.sql]

### Use um navegador de sua preferencia: Exemplo Google Chrome
 - Aponte para o servidor Tomcat: http://localhost:8080/CRUDJava/
