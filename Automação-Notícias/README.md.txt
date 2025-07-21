# 🧠 Automação MAKE: Coletor de Notícias com OpenAI, Airtable e Outlook

Este repositório contém um fluxo automatizado criado na plataforma [Make.com](https://make.com), com integração entre **OpenAI (ChatGPT)**, **Airtable** e **Outlook**, com o objetivo de buscar notícias atuais sobre determinado assunto e gerar um rascunho de e-mail com os dados estruturados.

---

## 🚀 Visão Geral do Projeto

A automação funciona em 3 etapas principais:

1. **Busca Inteligente com OpenAI**  
   A partir de um prompt (assunto ou tema), o módulo do ChatGPT retorna um resumo com as notícias mais atuais sobre o tópico pesquisado.

2. **Armazenamento no Airtable**  
   O conteúdo gerado é salvo automaticamente em uma tabela do Airtable, contendo:
   - **Título** (referente à notícia ou tema)
   - **Resumo gerado pela IA**
   - **Data da criação**

3. **Criação de Rascunho no Outlook**  
   Com base nas informações geradas e armazenadas, a automação cria um **rascunho de e-mail no Outlook**, já formatado, para posterior envio a um superior ou uso próprio.

---

## 🛠️ Ferramentas Utilizadas

- [Make.com](https://make.com) – plataforma de automação visual
- [OpenAI](https://platform.openai.com/) – geração de conteúdo com o modelo ChatGPT
- [Airtable](https://airtable.com) – banco de dados online tipo planilha
- [Microsoft Outlook](https://outlook.live.com) – criação do rascunho de e-mail

---

## 🧩 Fluxo do Cenário

```text
[Disparo manual ou agendado]
      ↓
[Prompt enviado ao ChatGPT]
      ↓
[Resposta formatada (notícia resumida)]
      ↓
[Salva dados no Airtable (título + conteúdo)]
      ↓
[Cria rascunho no Outlook com o conteúdo]
