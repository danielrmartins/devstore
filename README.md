
# devstore

Este repositório contém o código do devstore, um projeto de e-commerce usando o Next.js com Server Components. O projeto terá funcionalidades básicas, como listagem de produtos, carrinho e busca.

## 🎯 Objetivo

Aprendizado com as novas tecnologias do Next.js

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## 🚀 Tecnologias Utilizadas

### Frontend

- **Next.js:** Framework React para renderização do lado do servidor e geração de sites estáticos.
- **React:** Biblioteca JavaScript para construção de interfaces.
- **Lucide React:** Biblioteca de ícones leves e modernos.
- **Tailwind CSS:** Framework CSS para estilização rápida e responsiva.
- **Tailwind Merge:** Utilitário para combinar classes Tailwind sem conflito.
- **Zod:** Biblioteca de validação de dados para garantir a segurança e a integridade das informações.

### Configuração e Ambiente

- **@t3-oss/env-nextjs:** Gerenciamento de variáveis de ambiente no Next.js.

### Desenvolvimento e Qualidade de Código

- **ESLint e @rocketseat/eslint-config:** Linter para assegurar a qualidade do código.
- **TypeScript:** Superset do JavaScript para adicionar tipagem estática ao projeto.

### Testes

- **Cypress:** Framework de testes end-to-end para garantir a confiabilidade do sistema.

## 🔧 Instalação e Configuração

1. Clone o repositório:

```bash
git clone https://github.com/danielrmartins/devstore.git
```

2. Instale as dependências:

```bash
cd devstore
npm install
```

3. Configure as variáveis de ambiente:

- Crie o arquivo .env.local
- Adicione as variáveis de ambiente 

```bash
APP_URL="http://localhost:3000"
NEXT_PUBLIC_API_BASE_URL="https://devstore-api-navy.vercel.app/"

ou 

NEXT_PUBLIC_API_BASE_URL="http://localhost:3000"
```

4. Execute o servidor de desenvolvimento:

```bash
npm run dev
```

## 📄 Licença

Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo LICENSE.

