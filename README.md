# Chatbot para Criação de Provas com IA 🤖📝

Este projeto consiste em um chatbot desenvolvido para auxiliar estudantes na criação de perguntas para provas e simulados com base em material de estudo em PDF e provas de exemplo.

## Funcionalidades

- **Extração de Texto de PDFs:** O chatbot é capaz de extrair texto de arquivos PDF de material de estudo hospedados em repositórios do GitHub.
- **Análise de Provas de Exemplo:** Opcionalmente, o chatbot pode analisar provas de exemplo para entender o estilo e a dificuldade das perguntas.
- **Geração de Perguntas:** Utilizando o modelo de linguagem Google Gemini, o chatbot gera perguntas com alternativas baseadas no texto extraído.
- **Interface Interativa:** Oferece uma interface interativa no Google Colab para os usuários responderem às perguntas.
- **Feedback Automático:** Após o usuário responder às perguntas, o chatbot fornece feedback com a nota do usuário e as respostas corretas.

## Tecnologias Utilizadas

- **Google Gemini (`gemini-inst`):** Modelo de linguagem utilizado para geração de perguntas.
- **PyMuPDF:** Biblioteca para extração de texto de arquivos PDF.
- **spaCy:** Biblioteca de processamento de linguagem natural para análise de texto.
- **NLTK (WordNet):** Ferramenta para acesso a dicionários de sinônimos e antônimos.

## Como Usar no Google Colab

1. **Abra o projeto no Google Colab:**
   
2. **Configuração da API Key:**
   - Insira sua API key do Google no ambiente do Colab.
   - Certifique-se de executar esta etapa antes de utilizar o chatbot.
   ```python
   import os
   os.environ['GOOGLE_API_KEY'] = 'sua_api'
   ```
3. **Execute todas as funções**
   

3. **Configuração da API Key:**
   - Insira sua API key do Google no ambiente do Colab.
   - Certifique-se de executar esta etapa antes de utilizar o chatbot.
   ```python
   import os
   os.environ['GOOGLE_API_KEY'] = 'sua_api'
   ```

4. **Execução do Chatbot:**
   - Execute o código do chatbot no Google Colab.
   - Siga as instruções para fornecer as URLs dos PDFs e interagir com o chatbot.

## Observações

- Certifique-se de que as URLs fornecidas estão acessíveis e contêm os arquivos PDF corretos.
- O desempenho do chatbot pode variar dependendo da qualidade do texto do PDF e da disponibilidade de uma prova de exemplo.
- Este projeto é apenas para fins educacionais e pode ser expandido com mais funcionalidades e aprimoramentos.

Divirta-se estudando e criando suas próprias perguntas com o chatbot! 📚✨
