# Chatbot para Criação de Provas com IA 🤖📝

Este projeto consiste em um chatbot que utiliza inteligência artificial para auxiliar estudantes na criação de perguntas para provas e simulados com base em material de estudo em PDF e provas de exemplo.

## Funcionalidades

- **Extração de Texto de PDFs:** O chatbot extrai texto de arquivos PDF de material de estudo hospedados em repositórios do GitHub.
- **Análise de Provas de Exemplo:** Opcionalmente, o chatbot pode analisar provas de exemplo para entender o estilo e a dificuldade das perguntas.
- **Geração de Perguntas:** Utilizando o modelo de linguagem Google Gemini, o chatbot gera perguntas com alternativas baseadas no texto extraído.
- **Interface Interativa:** O chatbot oferece uma interface interativa para os usuários responderem às perguntas.
- **Feedback Automático:** Após o usuário responder às perguntas, o chatbot fornece feedback com a nota do usuário e as respostas corretas.

## Tecnologias Utilizadas

- **Google Gemini (`gemini-inst`):** Modelo de linguagem utilizado para geração de perguntas.
- **PyMuPDF:** Biblioteca para extração de texto de arquivos PDF.
- **spaCy:** Biblioteca de processamento de linguagem natural para análise de texto.
- **NLTK (WordNet):** Ferramenta para acesso a dicionários de sinônimos e antônimos.

## Como Usar

1. **Instalação:**
   - Clone este repositório para o seu ambiente local.
   - Certifique-se de ter todas as dependências instaladas (spacy, nltk, etc.).

2. **Configuração da API Key:**
   - Insira sua API key do Google no arquivo `.env` no campo `GOOGLE_API_KEY`.

3. **Execução:**
   - Execute o arquivo principal do chatbot.
   - Forneça a URL do repositório onde o PDF do material de estudo está armazenado.
   - Opcionalmente, forneça a URL de um PDF com uma prova de exemplo.
   - O chatbot irá gerar perguntas com base no texto do PDF e na prova de exemplo (se fornecida).
   - Responda às perguntas apresentadas na interface interativa.
   - Ao final, o chatbot apresentará sua nota e as respostas corretas.

## Observações

- Certifique-se de que as URLs fornecidas estão acessíveis e contêm os arquivos PDF corretos.
- O desempenho do chatbot pode variar dependendo da qualidade do texto do PDF e da disponibilidade de uma prova de exemplo.
- Este projeto é apenas para fins educacionais e pode ser expandido com mais funcionalidades e aprimoramentos.

Divirta-se estudando e criando suas próprias perguntas com o chatbot! 📚✨
