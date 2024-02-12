# lab-azure-ai-search
<br>
<strong>Criado:</strong><br>
    - Mecanismo de Busca<br>
    - Recurso de IA<br>
    - Storage Account<br>
<br>
<strong>Usei esta parte do doc para baixar os arquivos de exemplo:</strong><br>
    In a new browser tab, download the zipped coffee reviews from https://aka.ms/mslearn-coffee-reviews, and extract the files to the reviews folder.<br>
<br>
<strong>Realizado também a conexão entre o Blob Storage e o serviço Azure AI Search</strong><br>
    <br>[Index the documents]<br>
    2. On the Connect to your data page, in the Data Source list, select Azure Blob Storage. Complete the data store details with the following values:<br>
    Data Source: Azure Blob Storage<br>
    Data source name: coffee-customer-data<br>
    Data to extract: Content and metadata<br>
    Parsing mode: Default<br>
    Connection string: *Select Choose an existing connection. Select your storage account, select the coffee-reviews container, and then click Select.<br>
    Managed identity authentication: None<br>
    Container name: this setting is auto-populated after you choose an existing connection.<br>
    Blob folder: Leave this blank.<br>
    Description: Reviews for Fourth Cof<br>fee shops.<br>
<br>
<strong>Referencia</strong><br>
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
