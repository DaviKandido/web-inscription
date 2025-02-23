# 🎟️ Plataforma de Inscrição em Eventos - Web Incription

🚀 Um sistema de **inscrição em eventos** que contabiliza o número de **inscritos**, **indicações** e exibe um **ranking dos maiores indicadores**. Desenvolvido com **Next.js**, **React**, **TypeScript**, **Fastify**, **Tailwind CSS 4** e diversas bibliotecas React para otimizar a experiência do usuário.

## 🛠 Tecnologias

- **Frontend:** Next.js (React, TypeScript, TailwindCSS 4)
- **Backend:** Fastify (TypeScript)
- **Banco de Dados:** PostgreSQL
- **Autenticação:** NextAuth.js
- **Gerenciamento de Estado:** Zustand
- **Validação & Formulários:** react-hook-form, zod, @hookform/resolvers
- **API & Tipagem Automática:** orval
- **Ícones:** Lucide React

## 🎯 Funcionalidades

✅ **Cadastro de Inscrições:** Formulário dinâmico e validado  
✅ **Contabilização de Indicações:** Número de indicações por usuário  
✅ **Ranking de Indicadores:** Exibição dos usuários com mais indicações  
✅ **Interface Responsiva:** Layout adaptado para todos os dispositivos  
✅ **Performance Otimizada:** Next.js para SSR e SSG

---

# 🚀 Configuração do Projeto

### Criando o projeto Next.js sem configurações iniciais

```sh
npx create-next-app@latest --empty
```

## 📌 Instalação das Dependências

Execute o seguinte comando no terminal para instalar todas as dependências do projeto:

```sh
npm install @tailwindcss/postcss lucide-react next postcss react react-dom tailwindcss react-hook-form zod @hookform/resolvers orval
```

Para instalar as dependências de desenvolvimento, utilize:

```sh
npm install -D @biomejs/biome @types/node @types/react @types/react-dom typescript
```

---

## 📦 Dependências Individuais

| Pacote                   | Instalação                                        | Descrição                                                |
| ------------------------ | ------------------------------------------------- | -------------------------------------------------------- |
| **@tailwindcss/postcss** | `npm install @tailwindcss/postcss`                | Plugin oficial do Tailwind para integração com PostCSS.  |
| **lucide-react**         | `npm install lucide-react`                        | Conjunto de ícones otimizados para React.                |
| **next**                 | `npm install next`                                | Framework React para aplicações web otimizadas.          |
| **postcss**              | `npm install postcss`                             | Processador de CSS utilizado pelo Tailwind.              |
| **react**                | `npm install react`                               | Biblioteca principal para construção de interfaces.      |
| **react-dom**            | `npm install react-dom`                           | Pacote para manipulação da árvore DOM no React.          |
| **tailwindcss**          | `npm install tailwindcss`                         | Framework CSS utilitário para estilização rápida.        |
| **react-hook-form**      | `npm install react-hook-form`                     | Biblioteca para manipulação de formulários no React.     |
| **zod**                  | `npm install zod`                                 | Biblioteca para validação de schemas de entrada.         |
| **@hookform/resolvers**  | `npm install @hookform/resolvers`                 | Adaptadores para validação com react-hook-form e Zod.    |
| **orval**                | `npm install orval -D`                            | Gerador de código para APIs baseado em OpenAPI/Swagger.  |
| **@biomejs/biome**       | `npm install -D @biomejs/biome && npx biome init` | Ferramenta para linting, formatação e análise de código. |
| **@types/node**          | `npm install -D @types/node`                      | Tipos para o Node.js.                                    |
| **@types/react**         | `npm install -D @types/react`                     | Tipos para o React.                                      |
| **@types/react-dom**     | `npm install -D @types/react-dom`                 | Tipos para o React DOM.                                  |
| **typescript**           | `npm install -D typescript`                       | Suporte para TypeScript no projeto.                      |

---

## 🔧 Configuração do Tailwind CSS

Após instalar o Tailwind, inicialize a configuração com:

```sh
npx tailwindcss init -p
```

Isso criará os arquivos `tailwind.config.js` e `postcss.config.js`.

Edite o `tailwind.config.js` para incluir os caminhos dos seus arquivos:

```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

---

## 🚀 Como Executar

1️⃣ Clone o repositório:

```sh
git clone https://github.com/seu-usuario/web-inscription.git
```

2️⃣ Instale as dependências:

```sh
cd Next_FrontEnd
npm install

cd Fasyfy_BackEnd
npm install


```

3️⃣ Configure as variáveis de ambiente no arquivo `.env`

4️⃣ Inicie o backend:

```sh
npm run dev
```

5️⃣ Inicie o frontend:

```sh
npm run dev
```

---

## 📌 Contribuição

Sinta-se à vontade para abrir **issues** ou enviar **pull requests** para melhorias!

📩 Entre em contato: *davicandidopucminas@email.com*
