## 💻 MedApp

Simula a administração de um consultório, onde:

- O médico gerencia pacientes, consultas e receitas/prescrições.
- Uma consulta pode gerar prescrições relacionadas a um médico.

### Estrutura

```
/
├── MediApp/
│   ├── medi-app/    ← Frontend (Next.js/React + TypeScript)
│   └── src/         ← Backend (Node.js + Express + MongoDB)
├── ConsultorioMedico-drawio.png
├── Mod2/
├── Mod4/
├── ...
└── README.md
```

---

## ⚙️ Pré-requisitos

- Node.js instalado
- IDE de preferência (ex.: VS Code)  
- Navegador (ex.: Chrome)  
- MongoDB Compass (para gerenciamento local do banco)  
- Conta no Postman (opcional usar versão desktop)

---

## 🚀 Como executar

### Backend

```bash
cd MediApp/src
npm install
node index.js
```
Ou utilize plugin como CodeRunner pelo VS Code.

### Frontend

```bash
cd MediApp/medi-app
npm install
npm run dev
```

> Utilize terminais distintos e portas diferentes para backend e frontend.

⚠️ No Postman, carregue o arquivo de **environment** e ajuste a porta da API nos testes.

---

## ✨ Funcionalidades implementadas

- CRUD de médicos, pacientes e consultas
- Criação de prescrições dentro do escopo de uma consulta
- Páginas de listagem e edição no frontend
- Controle de autenticação (token)
- Pequenas melhorias de estilo e alertas via `map()`
- Suporte a upload de arquivos e exclusão de consultas

---

## 📝 Licença

Este projeto foi desenvolvido como parte da disciplina **Programação II** da **Faculdade Descomplica** e é disponibilizado exclusivamente para fins educacionais.

O uso, modificação e redistribuição do conteúdo são permitidos, desde que mantidos os devidos créditos aos autores e à instituição.  

---
