**in.Orbit**
Uma aplicação para gerenciamento de metas gamificada, onde o usuário cadastra metas semanais e pode controlar em tempo real a pontuação.

## Back-End
- Neste módulo, foi desenvolvido toda API da nossa aplicação, contendo configurações de rotas e use cases com todas as funcionalidades. 
- Desenvolvimento de uma aplicação back-end em Node.js, aplicação dos conceitos de API REST, utilizando TypeScript, Fastify como framework, integração do DrizzleORM + PostgreSQL, Docker e Zod para validação de dados.

### Tecnologias no Back-End

As seguintes ferramentas foram usadas neste projeto:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
  - Instalação: `npm i typescript -D`
  - Inicializar TypeScript: `npx tsx -init`
  - Configuração do tsconfig bases: [tsconfig bases (GitHub repo)](https://github.com/tsconfig/bases)

- [@types/node](https://www.npmjs.com/package/@types/node) e [TSX](https://www.npmjs.com/package/tsx)
  - Instalação: `npm i @types/node tsx -D`

- [Fastify](https://www.fastify.io/)
  - Instalação: `npm i fastify`

- [Biome](https://biomejs.dev/)
  - Instalação: `npm i -D --save-exact @biomejs/biome`

- [Drizzle ORM](https://orm.drizzle.team/)
  - Instalação: `npm i drizzle-orm`
  - Instalação do CLI: `npm i drizzle-kit -D`
  - Gerar migrações: `npx drizzle-kit generate`
  - Aplicar migrações: `npx drizzle-kit migrate`

- [Zod](https://www.npmjs.com/package/zod)
  - Instalação: `npm i zod`

- [Postgres](https://www.npmjs.com/package/postgres)
  - Instalação: `npm i postgres`

- [Cuid2](https://www.npmjs.com/package/@paralleldrive/cuid2)
  - Instalação: `npm i @paralleldrive/cuid2`

- [Day.js](https://day.js.org/)
  - Instalação: `npm i dayjs`

- [Fastify Type Provider Zod](https://www.npmjs.com/package/fastify-type-provider-zod)
  - Instalação: `npm i fastify-type-provider-zod`


## Front-End
- Neste módulo, foi desenvolvido uma aplicação web para criar metas semanais e acompanhar o progresso das metas cumpridas.
- Desenvolvimento de uma aplicação front-end em ReactJS, aplicação dos conceitos de Propriedades, Estados e Componentes, tipagem com Typescript, tooling com Vite, interface responsiva com TailwindCSS, consumo de API Node.js, gerenciamento de dados assíncronos com TanStack Query.


### Tecnologias do Front-End

| Ferramenta      | Descrição                                                                               |
| --------------- | --------------------------------------------------------------------------------------- |
| [ReactJs](https://react.dev/) | Biblioteca JavaScript para construir interfaces de usuário.                |
| [TypeScript](https://www.typescriptlang.org/) | Superset do JavaScript que adiciona tipagem estática.         |
| [Vite](https://vitejs.dev/)   | Ferramenta de build rápida para projetos web modernos.                     |
|                               | Instalação: `npm create vite@latest`                                       |
|                               | Inicializar projeto com Vite: `npm create vite@latest my-app`              |

---

### Bibliotecas

| Biblioteca      | Instalação                                                                              |
| --------------- | --------------------------------------------------------------------------------------- |
| [Biome](https://biomejs.dev/)                  | `npm i @biomejs/biome -D`                                       |
| [Tailwind CSS](https://tailwindcss.com/)       | `npm install -D tailwindcss postcss autoprefixer`               |
| PostCSS e Autoprefixer                         | Inicializar Tailwind: `npx tailwindcss init -p`                 |
| [Lucide React](https://www.npmjs.com/package/lucide-react) | `npm i lucide-react`                                         |
| [Tailwind Merge](https://www.npmjs.com/package/tailwind-merge) | `npm i tailwind-merge`                                   |
| [Radix UI - Radio Group](https://www.npmjs.com/package/@radix-ui/react-radio-group) | `npm i @radix-ui/react-radio-group` |
| [Radix UI - Progress](https://www.npmjs.com/package/@radix-ui/react-progress) | `npm i @radix-ui/react-progress` |
| [Radix UI - Dialog](https://www.npmjs.com/package/@radix-ui/react-dialog) | `npm i @radix-ui/react-dialog`   |
| [Tailwind Variants](https://www.npmjs.com/package/tailwind-variants) | `npm i tailwind-variants`             |
| [TanStack React Query](https://tanstack.com/query/latest) | `npm i @tanstack/react-query`                             |
| [Day.js](https://day.js.org/)                 | `npm i dayjs`                                                   |
| [React Hook Form](https://react-hook-form.com/) e [HookForm Resolvers](https://www.npmjs.com/package/@hookform/resolvers) | `npm i react-hook-form @hookform/resolvers` |
| [Zod](https://www.npmjs.com/package/zod)      | `npm i zod`                                                     |


## :memo: Licença ##
 MIT License. Para mais detalhes veja em [LICENSE](./LICENSE).

&#xa0;

_**Feito por <a href="https://github.com/fatalite38" target="_blank">Luiz Fernando</a>**_  👨‍🚀

<a href="#top">Back to top</a>