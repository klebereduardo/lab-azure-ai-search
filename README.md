# lab-azure-ai-search

Criado:
    - Mecanismo de Busca
    - Recurso de IA
    - Storage Account

Usei esta parte do doc para baixar os arquivos de exemplo:
    In a new browser tab, download the zipped coffee reviews from https://aka.ms/mslearn-coffee-reviews, and extract the files to the reviews folder.

Realiazado também a conexão entre o Blob Storage e o serviço Azure AI Search
    [Index the documents]
    2. On the Connect to your data page, in the Data Source list, select Azure Blob Storage. Complete the data store details with the following values:
    Data Source: Azure Blob Storage
    Data source name: coffee-customer-data
    Data to extract: Content and metadata
    Parsing mode: Default
    Connection string: *Select Choose an existing connection. Select your storage account, select the coffee-reviews container, and then click Select.
    Managed identity authentication: None
    Container name: this setting is auto-populated after you choose an existing connection.
    Blob folder: Leave this blank.
    Description: Reviews for Fourth Coffee shops.


Referencia
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
