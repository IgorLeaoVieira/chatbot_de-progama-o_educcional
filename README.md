# chatbot_de-progama-o_educcional
Chatbot educacional para ajudar no aprendizado de linguagens de programação com explicações, exemplos de código e execução passo a passo.
O chatbot pode ser usado para estudar linguagens como:

Python
JavaScript
Java
C / C++
C#
Go
Ruby
SQL
🎯 Objetivo

Criar um assistente interativo que:

Explica conceitos de programação de forma simples
Mostra exemplos práticos de código
Simula execução linha por linha
Ajuda na prática de lógica de programação
Corrige erros comuns de iniciantes
Sugere exercícios
🧠 Funcionalidades
1. Explicação de Conceitos

O bot responde perguntas como:

O que é uma variável?
O que é um loop?
Diferença entre lista e array?
2. Exemplos de Código

O chatbot fornece exemplos claros:

for i in range(5):
    print(i)
3. Execução Passo a Passo (Step Execution)

O sistema simula a execução do código:

Exemplo:

Código:

x = 2
y = 3
z = x + y
print(z)

Execução:

Linha 1: x recebe 2
Linha 2: y recebe 3
Linha 3: z recebe 5
Linha 4: imprime 5
4. Correção de Erros

O chatbot identifica erros comuns:

Exemplo:

print("Olá"

Resposta:

Erro: falta de parêntese de fechamento
Correção:
print("Olá")
5. Modo de Exercícios

O bot pode gerar desafios:

Escreva um programa que soma dois números
Crie um loop que imprime de 1 a 10
🏗️ Arquitetura do Sistema
Estrutura básica do projeto:
chatbot-educacional/
│
├── src/
│   ├── main.py
│   ├── chatbot.py
│   ├── parser.py
│   ├── executor.py
│   ├── knowledge_base.py
│
├── tests/
│   ├── test_chatbot.py
│
├── README.md
├── requirements.txt
└── config.py
⚙️ Módulos
1. chatbot.py

Responsável pela lógica principal de conversa.

Funções:

interpretar pergunta
chamar módulos corretos
gerar resposta
2. parser.py

Analisa código enviado pelo usuário.

Funções:

identificar linguagem
separar linhas
detectar erros básicos
3. executor.py

Simula execução do código passo a passo.

Funções:

rastrear variáveis
mostrar mudanças por linha
gerar explicação da execução
4. knowledge_base.py

Base de conhecimento com:

definições
exemplos
explicações prontas
💻 Exemplo de Uso

Entrada do usuário:

Explique este código:
x = 10
y = x + 5
print(y)

Saída do bot:

Este código cria uma variável x com valor 10.
Depois cria y somando x + 5.
Por fim imprime 15.
🧪 Tecnologias sugeridas
Python 3.x
Flask (API opcional)
FastAPI (alternativa moderna)
OpenAI API (opcional)
SQLite ou JSON (base simples)
React (interface web opcional)
🚀 Como rodar o projeto
# clonar repositório
git clone https://github.com/seu-usuario/chatbot-educacional

# entrar na pasta
cd chatbot-educacional

# instalar dependências
pip install -r requirements.txt

# executar
python src/main.py
