
# Classificador de Produtos com GenAI

## Descrição do Projeto

Este projeto visa criar um classificador de produtos para marketplaces utilizando **IA Generativa**. A partir do nome e descrição de um produto, o modelo irá classificar sua categoria. A solução utiliza o **LangChain** para integração com **modelos LLMs** da **Azure OpenAI**.

### Como Funciona

O projeto é estruturado em um notebook Jupyter onde:

1. **Pré-processamento**: Os dados de produtos são carregados, limpos e preparados para o modelo.
2. **Classificação de Categorias**: Usamos um modelo LLM para classificar o produto baseado no nome e descrição.
3. **Validação**: A categoria gerada pelo modelo é comparada com a categoria fornecida pelo vendedor para validar a classificação.

### Ferramentas Utilizadas

- **Azure OpenAI**: Para obter a chave de API, você deve se inscrever na plataforma Azure AI e criar uma chave de API para usar com o LangChain.
- **LangChain**: Biblioteca usada para integrar com a LLM e realizar o processo de classificação.
- **Pandas**: Para manipulação e análise dos dados.
- **Jupyter Notebook**: Ambiente para execução e análise interativa do código.

### Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/classificador-de-produtos-com-genai.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd classificador-de-produtos-com-genai
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. **Criação da chave da API**:
   - Crie uma conta no **Azure AI** (https://azure.microsoft.com) e gere uma chave para a API **OpenAI**.
   - No arquivo `Classificador_de_Produtos.ipynb`, substitua as variáveis correspondentes para integrar sua chave da API.

5. Execute o notebook:
   - Abra o notebook `Classificador_de_Produtos.ipynb` no Jupyter Notebook ou JupyterLab.
   - Execute as células do notebook para ver o processo de classificação em ação.

### Estrutura de Diretórios

- **data/produtos.csv**: Exemplo de dados de produtos com nome, descrição e categoria.
- **notebooks/Classificador_de_Produtos.ipynb**: Notebook Jupyter para executar o projeto e testar a classificação.

## 👤 Autor

- [Gustavo Ribeiro](https://github.com/queirozene)
- [LinkedIn](https://www.linkedin.com/in/guxtavoqr/)
