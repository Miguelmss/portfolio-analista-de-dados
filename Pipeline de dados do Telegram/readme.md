# Pipeline de ETL para Dados do Telegram  

Este projeto tem como objetivo desenvolver um processo de **ETL (Extração, Transformação e Carregamento)** para coletar mensagens de um grupo no Telegram e disponibilizá-las para análise no AWS Athena. A implementação utiliza **APIs, AWS Lambda e AWS S3**, garantindo um fluxo eficiente e automatizado de dados.  

---

## Passo a Passo do Projeto  

1. **Extração dos Dados**  
   - Utilização da API do Telegram para coletar mensagens de um grupo específico.  

2. **Transformação dos Dados**  
   - Processamento das mensagens utilizando uma **função Lambda na AWS**, convertendo os dados para um formato estruturado.  

3. **Armazenamento dos Dados**  
   - Salvamento dos dados transformados no **AWS S3** em um formato compatível com SQL.  

4. **Consulta e Análise**  
   - Configuração do **AWS Athena** para executar queries SQL sobre os dados armazenados.  

---

## Tecnologias e Ferramentas Utilizadas  

- **Python**: Manipulação e processamento de dados.  
- **API do Telegram**: Extração de mensagens em tempo real.  
- **AWS Lambda**: Transformação automatizada dos dados.  
- **AWS S3**: Armazenamento eficiente para análise.  
- **AWS Athena**: Consulta SQL sobre os dados armazenados.  

---

## Competências Desenvolvidas  

- Construção de Pipelines de Dados  
- Integração de APIs  
- Automação com AWS Lambda  
- Processamento e Análise de Dados  

---

Este projeto demonstra minha capacidade de construir pipelines de dados eficientes e escaláveis, integrando múltiplas tecnologias para transformar e analisar informações de forma automatizada.  

