<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/619af8f8-d138-4e40-9d48-fec7b318e44d.png"></a>
    <span> 
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados</span>
</h1>

## Problema:

O desafio propoe que seja criada uma pesquisa que funcione juntamente com um serviço de inteligência artificial para identificar palavras chave, sentimentos, utilizando também o serviço de armazenamento do azure.

[Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Criando recurso do Azure AI Search:     

![alt text](img/01.PNG)

## Criando recurso do Azure AI services:      

![alt text](img/02.PNG)

## Criando o storage:      

![alt text](img/05.PNG)

## Permitindo acesso anônimo ao Blob:      

![alt text](img/06.PNG)


## Importação e indexação dados para o AI SEARCH:      

![alt text](img/08.PNG)

##  Cnsultando o índice:      

Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:

![alt text](img/09.PNG)

```
search=*&$count=true    (  verifica se a indexação esta funcionando e mostra os documentos )
```
![alt text](img/09.PNG)

```
search=locations:'Chicago' ( Consulta as ocorrencias acontecidas em Chicado )
```
![alt text](img/10.PNG)

```
search=sentiment:'negative' ( Consulta as ocorrencias com sentimento negativo )
```
![alt text](img/11.PNG)


## Observações finais:      

As ferramentas de inteligência artificial do Azure facilitam a consulta em documentos, pesquisas e depoimentos, agilizando ainda mais a consulta de satisfação de empresas sobre seus produtos e serviços.