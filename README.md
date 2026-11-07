# Base de conhecimento: Chatbot VAMOS

Conteúdo que a assistente virtual da Vamos consulta para responder leads no WhatsApp.

> **Atenção: este repositório é público.** Coloque aqui só o que a IA pode dizer a qualquer pessoa. Nada de margens, tabelas internas, dados de clientes, contatos pessoais ou senhas.

## Como funciona

- A IA lê **todos os arquivos `.md`, `.mdx` e `.txt` da pasta [`kb/`](kb/)**. Este README fica de fora.
- Um assunto por arquivo, em Markdown, com títulos claros (`##`). O nome do arquivo e os títulos ajudam a IA a achar a resposta.
- Depois de um push na `main`, o bot passa a usar a versão nova em até **10 minutos**.
- A IA responde **somente** com o que está aqui. Se a informação não estiver aqui, ela coleta os dados do lead e transfere para o Atendimento Comercial.

## Boas práticas

- Escreva como você explicaria para um vendedor novo: fatos, números e condições explícitas.
- Preço, prazo e condição comercial só entram se estiverem confirmados e puderem ser divulgados.
- Prefira perguntas e respostas (`## Pergunta?` seguido da resposta) para as dúvidas frequentes.
- Quando algo mudar, edite o arquivo existente em vez de criar outro com informação conflitante.

O código do chatbot fica em um repositório privado separado.
