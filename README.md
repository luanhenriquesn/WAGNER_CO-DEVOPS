# ENTREGÁVEL CHALLENGE - 4° SPRINT - DEVOPS

**Nome do Grupo:**  Wagner & CO

**Nome e RM dos Alunos:**

    Guilherme dos Santos Araújo - RM: 85719
    
    Luan Henrique Silva Neves – RM: 85181
    
    Rodrigo de Almeida Barbosa – RM: 85137
    
    William José Rangon de Lima – RM: 85970

**Turma:** 2TDSA

## Desenho do pipeline e um detalhamento de cada etapa criada, detalhando os benefícios a serem alcançados nessa fase
![ARQUITETURA_JENKINS](https://user-images.githubusercontent.com/63483424/138733242-4c7224ee-8536-45af-876f-25fb107ef3f5.jpg)

**Commit**

    Nesta etapa, o usuário está alterando o código fonte da aplicação no repositório GitHub.
    
**Check Out**

    Nesta etapa, o Jenkins está fazendo o check out do código fonte do repositório GitHub.

**Build**

    Nesta etapa, o Jenkins está utilizando o Maven para fazer o build da aplicação, gerando o arquivo .WAR.
    
**Deploy**

    Nesta etapa, caso o resnposável pela aprovação aprove o deploy, o Jenkins irá usar o TomCat para fazer o deploy do arquivo .WAR.


**Benefícios Alcançados**
    

## Link de vídeo demonstração

[Link para o video youtube](https://www.youtube.com/watch?v=asU3WQ_vJ6s)

