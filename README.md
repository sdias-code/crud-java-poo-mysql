
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

### Configura��o e instala��o
- Java
  - Instala��o:
    - Instale a aplica��o normalmente
  - Configura��o:
    - N�o ha necessidade
- Eclipse
  - Instala��o:
    - Instale a aplica��o normalmente
  - Configura��o:
    - Com o Eclipse iniciado, v� em:
      - "File"
        - "Open Projects from File System"
          - Selecione o diret�rio que voc� baixou o reposit�rio da aplica��o e clique em "finish".
    - Clique no bot�o direito na pasta do projeto
      - V� em "Servers" (se encontra na parte inferior do programa, caso n�o tenha encontrado, procure por ele em "Quick Acess")
        - Clique para adicionar um novo servidor
          - Selecione "Tomcat v8.5 Server" e clique em Next
            - Selecione a pasta em que voc� baixou o "Tomcat 8.5"
            - Selecione o JRE como: jre_1.8.0_xxx e clique em "Finish"
- MySQL
  - Instala��o:
    - Instale a aplica��o normalmente
  - Configura��o:
    - Configure a porta do MySQL como padr�o (3306)
    
### Uso da aplica��o
Com o Eclipse rodando e o projeto selecionado, espere que o Maven baixe todas as depend�ncias do projeto, logo ap�s, verifique se o SQL est� rodando na porta 3306
- Baixe e execute o Script SQL: [crud_java.sql]

### Use um navegador de sua preferencia: Exemplo Google Chrome
 - Aponte para o servidor Tomcat: http://localhost:8080/CRUDJava/
