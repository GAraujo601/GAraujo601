# Hi there/ Olá. Meu nome é Gênesis.

Sou estudante do Bacharelado em Ciência e Tecnologia com foco em Ciência da Computação na UFABC, construo automações e ferramentas com IA. Abaixo, três projetos que fiz do zero, cada um com README, decisões de design e limitações.

## Projetos

### 1. Agenda diária com IA
Bot em Python que envia todo dia às 8h, no Telegram, a agenda do dia priorizada por um LLM (Gemini). Se a IA falhar, o bot manda a lista simples e não deixa de avisar.
- **Stack:** Python, API do Telegram, Gemini, Agendador de Tarefas do Windows
- **Destaques:** retentativas só em erros temporários, limite de 180 s, registro de cada execução em CSV
- **Resultado:** em processamento...
- [Repositório]https://github.com/GAraujo601/agenda_diaria_ia-telegram

### 2. Analisador de vagas (n8n + Gemini)
Workflow que recebe uma vaga (texto ou link) e um currículo, e devolve uma nota técnica com a evidência de cada requisito. A IA classifica e o código pontua, com regra fixa.
- **Stack:** n8n, Gemini, JavaScript
- **Destaques:** três categorias de requisito, evidência obrigatória, falha explícita quando faltam dados
- **O que medi:** a nota variou entre 38 e 75 em cinco execuções da mesma vaga, então ela deve ser lida como uma faixa, e as evidências por requisito são o que mais importa
- [Repositório]https://github.com/GAraujo601/analisador-de-vagas-n8n

### 3. Radar de Vagas
Painel publicado que mostra quais habilidades mais aparecem nas vagas que analiso e quais ainda faltam no meu perfil. Gerado no v0 a partir de prompt meu e revisado antes de publicar.
- **Stack:** Next.js, TypeScript, Tailwind, Recharts, API do Gemini
- **Destaques:** chave só no servidor, código de acesso e limite de texto na rota, erros tratados na tela
- [Demo](https://radar-de-vagas-beta.vercel.app/) · [Vídeo](https://github.com/user-attachments/assets/df108ff4-d224-449a-93a4-f884af2a8652) · [Repositório](https://github.com/GAraujo601/radar-de-vagas)

## Como trabalho

- Testo o que construo e registro o que não funcionou, nos READMEs.
- Não publico número que não consigo sustentar.
- Cuido de segredos e de dados pessoais antes de subir qualquer código.

## Contato

[https://linkedin.com/in/gaa1]
