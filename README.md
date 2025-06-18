# SaaS Agendamento Clínica

Sistema de agendamento para clínicas desenvolvido com as mais modernas tecnologias do mercado.

## 🚀 Tecnologias

### Core

- [Next.js 15](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [React 19](https://react.dev/)

### Estilização

- [Tailwind CSS](https://tailwindcss.com/)

### Banco de Dados

- [PostgreSQL](https://www.postgresql.org/)
- [Drizzle ORM](https://orm.drizzle.team/) - ORM para TypeScript
- [node-postgres (pg)](https://node-postgres.com/) - Driver PostgreSQL

### Desenvolvimento

- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [dotenv](https://www.npmjs.com/package/dotenv)

## 🛠️ Configuração do Ambiente

1. Clone o repositório

```bash
git clone https://github.com/Jimmy-Vaniski/Saas-agendamento-clinica.git
```

2. Instale as dependências

```bash
npm install
```

3. Configure as variáveis de ambiente
   Crie um arquivo `.env` na raiz do projeto com as seguintes variáveis:

```env
DATABASE_URL="sua-url-do-postgresql"
```

4. Execute o projeto em desenvolvimento

```bash
npm run dev
```

## 📝 Banco de Dados

### Estrutura

O projeto utiliza Drizzle ORM com PostgreSQL. A estrutura do banco inclui:

- Users (Usuários)
- Clinics (Clínicas)
- Doctors (Médicos)
- Patients (Pacientes)
- Appointments (Agendamentos)

### Comandos do Drizzle

```bash
# Aplicar migrações
npx drizzle-kit push
```

**Nota**: Execute os comandos do Drizzle no terminal CMD do Windows para melhor compatibilidade.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
