<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# Authentication Forms — React + Tailwind CSS

Projeto SPA didático com páginas Sign In e Sign Up. Interface de demonstração, sem servidor ou autenticação real.

## Requisitos
- Node.js em versão compatível com o Vite instalado
- npm
- Navegador moderno

## Instalação e execução
\`\`\`bash
npm install
npm run dev
\`\`\`

## Compilação
\`\`\`bash
npm run build
npm run preview
\`\`\`

## Arquitetura
- App.jsx: raiz da aplicação.
- pages/AuthPage.jsx: controle de alternância entre formulários.
- components/ui/Input.jsx: campos reutilizáveis e erros.
- components/ui/Button.jsx: botão reutilizável e loading.
- components/ui/SocialButton.jsx: botão social visual.
- components/ui/AuthBadge.jsx: etiqueta da página.
- components/auth/SignInForm.jsx: estado e validação do login.
- components/auth/SignUpForm.jsx: estado e validação do cadastro.
- components/auth/AuthDivider.jsx: linha divisória.
- components/auth/SocialLogin.jsx: composição de botões sociais.
- components/layout/BackgroundEffects.jsx: glows decorativos.
- index.css: Tailwind v4 e design tokens.

## Fluxo
Troque entre Sign In e Sign Up sem recarregar. Formulários usam input controlado, validação e simulação de loading. Não há autenticação real.

## Referência no Figma
https://www.figma.com/design/M9uYIV5AskfRFf2VgmtYwJ?node-id=2-29

## Entrega
Inclua capturas de tela Sign In / Sign Up, versão Node, versão Vite, testes e commits.

## Segurança
Não armazene senha no localStorage nem escreva senhas no console. O projeto não envia dados para servidor.
>>>>>>> d66d6f81f5fb17e81bb70a19a834cde718e6a191
