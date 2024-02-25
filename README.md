# Laboratório DIO - Análise de Sentimentos com Language Studio no Azure AI
> [!NOTE]
> É necessário ter uma conta do Azure
## Passo a passo Estúdio de fala
### 1. Configurando um recurso 
  - No menu de cima click em **configurações**
  - Caso não tenha nenhum recurso click em **Criar novo recurso**
  - Selecione o recurso
  - Click em **Usar o recurso**
  - Volte para a tela principal
### 2. Conversão de fala em texto
  - Click no card **Conversão de fala em texto em tempo real**
  - Selecione o checkbox
  - Pode explorar [documenção](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-to-text) e a [exemplos de código](https://github.com/Azure-Samples/cognitive-services-speech-sdk)
  - Teste fazendo upload de um arquivo de audio ou fale pelo microfone

## Passo a passo Language Studio 
### 1. Criar um recurso de Serviço de linguagem
  - Dentro do portal do [Azure](https://portal.azure.com/#home)
  - Click em **Criar recurso**
  - Crie **Análise de Texto**
  - **Continue to create your resource**
  - Preencher **Assinatura**, **Grupode recurso**, **Região** e **Nome**
  - Preencher **Tipo de preço** com *Free F0*
  - Selecione o checkbox
  - Examinar + criar
  - Criar
### 2. Language Studio
  - Entrar no [Language Studio](https://language.cognitive.azure.com/home)
  - **Select resource**
  - Preencher **Azure directory** e **Azure subscription**
  - Preencher **Resource type** com *Language*
  - Preencher **Resource name** com o recurso criado
  - Done
  - Vá para a aba **Classify text**
  - Click no card **Analyze sentiment and mine opinions**
  - Pode explorar [documenção](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/sentiment-opinion-mining/quickstart?tabs=linux&pivots=programming-language-csharp) e a [exemplos de código](https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/textanalytics/azure-ai-textanalytics/samples)
  - Selecione o checkbox
  - Teste fazendo upload de um arquivo de texto ou escreva no campo indicado
  - Exemplo de análise
    ![Img1](/inputs/language.cognitive.azure.png)
