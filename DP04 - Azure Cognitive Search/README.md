<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/619af8f8-d138-4e40-9d48-fec7b318e44d.png"></a>
    <span> 
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados</span>
</h1>

## Criando o laboraório

As etapas e configurações de criação do lab estão disponiveis na [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

### Resultados

#### Cnsultando o índice:

Use o Search Explorer para escrever e testar consultas. O explorador de pesquisa é uma ferramenta incorporada no portal do Azure que oferece uma maneira fácil de validar a qualidade do seu índice de pesquisa. Você pode usar o Search Explorer para escrever consultas e revisar resultados em JSON.

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/Imagens/LAB04/consultado%20ind%20lab04.png?raw=true" width=""/> ...

```
search=*&$count=true    (  verifica se a indexação esta funcionando e mostra os documentos )
```

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/Imagens/LAB04/status.png?raw=true" width=""/> ...

```
search=locations:'Chicago' ( Consulta as ocorrencias acontecidas em Chicado )
```

<img align="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/Imagens/LAB04/resultado%20cidade.png?raw=true" width=""/> ...

```
search=sentiment:'negative' ( Consulta as ocorrencias com sentimento negativo )
```

<img align="right" src="https://github.com/hjacauna/Dio--IA-Azure-Fundamentals/blob/main/Imagens/LAB04/resultado%20sentimento.png?raw=true" width=""/> ...

## Considerações finais

As ferramentas de Inteligência Artificial do Azure simplificam a busca em documentos, pesquisas e depoimentos, tornando ainda mais eficiente a análise da satisfação das empresas em relação aos seus produtos e serviços. Essas ferramentas permitem extrair informações relevantes de documentos, como textos, tabelas e estruturas, facilitando a tomada de decisões informadas e aprimorando a eficiência operaciona. É uma maneira inteligente de processar grandes volumes de dados armazenados em formulários e documentos, contribuindo para a inovação e o sucesso das organizações.
