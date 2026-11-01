# Hi there/ Olá. Meu nome é Gênesis.

**Sou estudante do Bacharelado em Ciência e Tecnologia com foco em Ciência da Computação na UFABC, construo automações e ferramentas com IA. Abaixo, três projetos que fiz do zero, cada um com README, decisões de design e limitações.**

Português nativo · Inglês avançado ·

Gosto de transformar uma tarefa repetitiva em algo que roda sozinho, e de ser claro sobre o que funcionou e o que não. Nas últimas semanas, construí e publiquei três projetos com IA, cada um com README, decisões de design, testes e limitações.
## Projetos com IA

### 1. Agenda diária com IA
Bot em Python que envia todo dia às 8h, no Telegram, a agenda do dia priorizada por um LLM (Gemini). Se a IA falhar, o bot manda a lista simples, então o aviso nunca deixa de chegar.
- **Stack:** Python, API do Telegram, Gemini, Agendador de Tarefas do Windows
- **Destaques:** novas tentativas só em erros temporários, limite de 180 s na etapa de IA, registro de cada execução em CSV e script de métricas
- **Resultado:** em uso diário desde 23/10/2026. -[Repositório](https://github.com/GAraujo601/agenda_diaria_ia-telegram)

### 2. Analisador de vagas (n8n + Gemini)
Workflow que recebe uma vaga (texto ou link) e um currículo, e devolve uma nota técnica com a evidência de cada requisito. A IA classifica e o código pontua, com regra fixa.
- **Stack:** n8n, Gemini, JavaScript
- **Destaques:** três categorias de requisito, evidência obrigatória, falha explícita quando faltam dados
- **O que medi:** a nota variou entre 38 e 75 em cinco execuções da mesma vaga, então ela deve ser lida como uma faixa, e as evidências por requisito são o que mais importa
- [Repositório](https://github.com/GAraujo601/analisador-de-vagas-n8n)

### 3. Radar de Vagas
Painel publicado que mostra quais habilidades mais aparecem nas vagas que analiso e quais ainda faltam no meu perfil. Gerado no v0 a partir de um prompt meu e revisado antes de publicar.
- **Stack:** Next.js, TypeScript, Tailwind, Recharts, API do Gemini
- **Destaques:** chave só no servidor, código de acesso e limite de texto na rota, erros tratados na tela
- [Demo](https://radar-de-vagas-beta.vercel.app/) · [Vídeo](https://github.com/user-attachments/assets/df108ff4-d224-449a-93a4-f884af2a8652) · [Repositório](https://github.com/GAraujo601/radar-de-vagas)

## Outros trabalhos

- **Site front-end (2022)projeto pessoal:** O objetivo deste site é facilitar o contato direto entre os clientes e a assistência técnica, oferecendo as seguintes funcionalidades:diagnóstico e orçamento, consulta de estoque e agendamento on-line.
 HTML, CSS, JavaScript e Bootstrap.
[Repositório](https://github.com/GAraujo601/GAraTech-st)

- **Avaliação de modelos de IA:** escrevi prompts e perguntas de acompanhamento, incluindo tentativas de jailbreak, para identificar e reduzir alucinações em respostas de modelos de linguagem. 
- **Back-end (curso):** teste de APIs com Postman e conexão a um banco MongoDB.

## Formação

- Bacharelado em Ciência e Tecnologia, com foco em Ciência da Computação, UFABC (2025 – presente
- Técnico em Perfuração e Produção de Petróleo, INP (2019–2023)
- Certificado de Cibersegurança do Google

## Liderança

- Presidente do Governo Estudantil de um acampamento de estudos (6 meses): liderou a equipe de representantes, coordenou reuniões e mediou conflitos entre estudantes e a administração.

## Como trabalho

- Testo o que construo e registro o que não funcionou, nos READMEs.
- Não publico número que não consigo sustentar.
- Cuido de segredos e de dados pessoais antes de subir qualquer código.

## Contato

[LinkedIn](https://linkedin.com/in/gaa1)




