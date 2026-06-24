# Modelagem MEAM

Sistema WEB de gerenciamento de apostas da Copa do Mundo desenvolvido utilizando a stack **MEAN (MongoDB, Express, Angular e Node.js)**.

## Tecnologias Utilizadas

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Frontend
- Angular
- TypeScript
- HTML5
- CSS3

### Controle de Versão
- Git
- GitHub

---

## Estrutura do Projeto

```text
modelagem-meam/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── database.js
│   │   ├── controllers/
│   │   │   ├── betController.js
│   │   │   └── matchController.js
│   │   ├── models/
│   │   │   ├── Bet.js
│   │   │   └── Match.js
│   │   ├── routes/
│   │   │   ├── betRoutes.js
│   │   │   └── matchRoutes.js
│   │   └── server.js
│   ├── package-lock.json
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   │   ├── app.config.ts
│   │   │   ├── app.css
│   │   │   ├── app.html
│   │   │   ├── app.routes.ts
│   │   │   ├── app.spec.ts
│   │   │   └── app.ts
│   │   ├── index.html
│   │   ├── main.ts
│   │   └── styles.css
│   ├── angular.json
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md

## Como Clonar o Projeto

```bash
git clone https://github.com/eliaferreira/modelagem-meam.git
cd modelagem-meam
```

## Instalação das Dependências

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd frontend
npm install
```

## Executando o MongoDB

### Iniciar o MongoDB

Execute o PowerShell como administrador:

```powershell
Start-Service MongoDB
```

### Verificar o Status do MongoDB

Execute o PowerShell como administrador:

```powershell
Get-Service MongoDB
```

## Executando o Backend

Abra um terminal na pasta `backend` e execute:

```bash
cd backend
npm run dev
```

O servidor será iniciado em:

```text
http://localhost:3001
```

Exemplo de rota disponível:

```text
http://localhost:3001/api/matches
```

## Executando o Frontend

Abra um terminal na pasta `frontend` e execute:

```bash
cd frontend
ng serve
```

A aplicação será iniciada em:

```text
http://localhost:4200
```

## Informações Acadêmicas

- **Professor:** WESLEY PEREIRA DA SILVA
- **Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas - FAESA
- **Disciplina:** Desenvolvimento e Aplicações WEB II
- **Semestre:** 2026/1