# FórumHub API
### Descrição
<p align="justify">
FórumHub é uma API REST desenvolvida em Java com Spring Boot, que simula um fórum de discussão. A API permite que os usuários criem, visualizem, atualizem e excluam tópicos de discussão, perfis, respostas, cursos e usuários. Apenas usuários autenticados podem interagir com a API. Este projeto faz parte do desafio Challenge Back End.
</p>

## Funcionalidades
A API FórumHub oferece as seguintes operações:

 - CRUD de Tópicos: Usuários autenticados podem criar, visualizar, atualizar e deletar tópicos de discussão. 
 - CRUD de Perfis: Usuários autenticados podem criar, visualizar, atualizar e deletar perfis.
 - CRUD de Respostas: Usuários autenticados podem criar, visualizar, atualizar e deletar respostas em tópicos.
 - CRUD de Cursos: Usuários autenticados podem criar, visualizar, atualizar e deletar cursos.
 - CRUD de Usuários: Administradores podem criar, visualizar, atualizar e deletar usuários. 

## Tecnologias Utilizadas

- Java: Linguagem de programação utilizada para desenvolver a API.
- Spring Boot: Framework utilizado para construir a API REST.
- Spring Security: Módulo de segurança do Spring utilizado para autenticação e controle de acesso.
- JWT (JSON Web Token): Utilizado para autenticação stateless e segura.
- auth0: Serviço de gestão de identidade e autenticação usado para integrar e gerenciar as credenciais dos usuários.
- Spring Doc: Utilizado para geração automática da documentação da API.
- MySQL: Banco de dados relacional utilizado para armazenamento dos dados.
Diagrama do Banco de Dados


## Pré-requisitos

Para executar o projeto, você precisará ter instalado:

<p>Java 11 ou superior;</p>
<p>Maven;</p>
<p>MySQL (instalado e configurado)</p>
<p>Como Configurar e Executar</p>
<p>Configurar Banco de Dados MySQL</p>
da API gerada pelo Spring Doc pode ser acessada em http://localhost:8080/swagger-ui.html.