<div align="center">

```
███████╗ ██████╗ ██████╗  ██████╗ ███████╗██████╗ ███████╗██╗   ██╗
██╔════╝██╔═══██╗██╔══██╗██╔════╝ ██╔════╝██╔══██╗██╔════╝██║   ██║
█████╗  ██║   ██║██████╔╝██║  ███╗█████╗  ██║  ██║█████╗  ██║   ██║
██╔══╝  ██║   ██║██╔══██╗██║   ██║██╔══╝  ██║  ██║██╔══╝  ╚██╗ ██╔╝
██║     ╚██████╔╝██║  ██║╚██████╔╝███████╗██████╔╝███████╗ ╚████╔╝ 
╚═╝      ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═════╝ ╚══════╝  ╚═══╝  
                                                              A P P S
```

### Site Institucional — React · TypeScript · Vite

<p>
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-6.x-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Twind-Tailwind-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/ESLint-configured-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/versão-1.0.0-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/licença-MIT-yellow?style=flat-square" />
  <img src="https://img.shields.io/badge/PRs-welcome-blueviolet?style=flat-square" />
</p>

<br/>


> **ForgeDev Apps** é um site institucional moderno, rápido e tipado — construído com o melhor do ecossistema frontend atual. Combina a robustez do **TypeScript**, a velocidade do **Vite** e a praticidade das classes utilitárias do **Twind/Tailwind CSS** para entregar uma experiência de desenvolvimento e de usuário de alto nível.

<br/>

[🌐 Demo ao Vivo](#) · [📖 Como Rodar](#️-instalação-e-execução) · [🐛 Reportar Bug](#) · [✨ Solicitar Feature](#)

-----

</div>

<br/>

## 📸 Preview

<div align="center">

|🖥️ Desktop                                    |📱 Mobile                              |
|:-------------------------------------------:|:------------------------------------:|
|*Página principal — hero, serviços e contato*|*Layout responsivo e navegação mobile*|


> 📌 **Dica:** Adicione capturas de tela reais da aplicação para causar a melhor primeira impressão!

</div>

<br/>

-----

## 🌟 Destaques do Projeto

```
✦ TypeScript do início ao fim — sem any, sem surpresas em produção
✦ Vite como bundler — HMR instantâneo e build otimizado com Rollup
✦ Twind/Tailwind CSS — estilização utilitária sem gerar arquivo CSS em disco
✦ Arquitetura de componentes limpa, escalável e reutilizável
✦ ESLint com plugins React — código padronizado e livre de más práticas
✦ Pronto para deploy em Vercel, Netlify ou qualquer CDN estático
```

<br/>

-----

## 🛠️ Stack Tecnológico

<div align="center">

|Categoria|Tecnologia            |Versão  |Papel no Projeto                             |
|:--------|:---------------------|:------:|:--------------------------------------------|
|⚛️ UI     |React                 |`19`    |Biblioteca principal de interface declarativa|
|🔷 Tipagem|TypeScript            |`5.x`   |Tipagem estática, autocomplete e segurança   |
|⚡ Bundler|Vite                  |`6.x`   |Dev server ultrarrápido + build otimizado    |
|🎨 Estilo |Twind / Tailwind CSS  |`latest`|Classes utilitárias inline, sem CSS em disco |
|🔍 Linter |ESLint + plugins React|`latest`|Padronização de código e boas práticas       |

</div>

<br/>

-----

## ⚙️ Instalação e Execução

### Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) `>= 20.x`
- [npm](https://www.npmjs.com/) `>= 9.x` *(ou [Yarn](https://yarnpkg.com/) / [pnpm](https://pnpm.io/))*

-----

### Passo 1 — Clone o Repositório

```bash
git clone https://github.com/seu-usuario/forgedev-apps.git
cd forgedev-apps
```

### Passo 2 — Instale as Dependências

```bash
npm install
```

### Passo 3 — Inicie o Servidor de Desenvolvimento

```bash
npm run dev
```

> 🌐 Acesse **`http://localhost:5173`** no seu navegador.  
> O Vite já sobe com **HMR (Hot Module Replacement)** ativo — cada alteração no código reflete instantaneamente na tela, sem precisar recarregar.

-----

### 📦 Scripts Disponíveis

|Comando          |Descrição                                          |
|:----------------|:--------------------------------------------------|
|`npm run dev`    |Inicia o servidor de desenvolvimento com HMR       |
|`npm run build`  |Gera o build de produção otimizado em `/dist`      |
|`npm run preview`|Serve o build de produção localmente para validação|
|`npm run lint`   |Analisa o código com ESLint e aponta problemas     |

<br/>

-----

## 🗂️ Estrutura do Projeto

```
forgedev-apps/
├── 📁 public/                  # Arquivos estáticos (favicon, robots.txt)
├── 📁 src/
│   ├── 📁 components/          # Componentes reutilizáveis (Button, Card, etc.)
│   │   ├── 📁 layout/          # Header, Footer, Section, Container
│   │   └── 📁 ui/              # Componentes de interface (Hero, Features, CTA)
│   ├── 📁 pages/               # Páginas da aplicação
│   ├── 📁 types/               # Tipos e interfaces TypeScript globais
│   ├── 📁 utils/               # Funções auxiliares e helpers
│   ├── App.tsx                 # Componente raiz e configuração de rotas
│   ├── main.tsx                # Entry point — monta o React na DOM
│   └── vite-env.d.ts           # Tipagens do ambiente Vite
├── .eslintrc.cjs               # Configuração do ESLint
├── tsconfig.json               # Configuração do TypeScript
├── vite.config.ts              # Configuração do Vite
├── package.json
└── README.md
```

<br/>

-----

## 🚀 Deploy

O projeto gera arquivos **100% estáticos** após o build — sem servidor necessário. Faça o deploy em qualquer plataforma de sua preferência:

<div align="center">

|Plataforma          |Configuração                                                        |
|:-------------------|:-------------------------------------------------------------------|
|**Vercel**          |Conecte o repositório — detecta Vite automaticamente ✅              |
|**Netlify**         |Build command: `npm run build` · Publish dir: `dist`                |
|**GitHub Pages**    |Use a action `vite-gh-pages` ou configure `base` no `vite.config.ts`|
|**Cloudflare Pages**|Build command: `npm run build` · Output dir: `dist`                 |

</div>

<br/>

-----

## 🗺️ Roadmap

- [x] Estrutura inicial com React + TypeScript + Vite
- [x] Estilização com Twind / Tailwind CSS
- [x] Configuração de ESLint com plugins React
- [x] Layout responsivo mobile-first
- [ ] 🔜 Animações de entrada com Framer Motion
- [ ] 🔜 Formulário de contato funcional (EmailJS ou Resend)
- [ ] 🔜 Internacionalização PT-BR / EN (i18next)
- [ ] 🔜 Testes unitários com Vitest + Testing Library
- [ ] 🔜 SEO e meta tags dinâmicas (React Helmet Async)
- [ ] 🔜 Dark Mode com toggle persistido

<br/>

-----

## 🤝 Como Contribuir

Toda contribuição é bem-vinda! Siga o fluxo abaixo:

```bash
# 1. Fork o projeto

# 2. Crie sua branch
git checkout -b feature/minha-feature

# 3. Faça suas alterações e commite seguindo Conventional Commits
git commit -m "feat: adiciona seção de depoimentos"

# 4. Envie para o repositório remoto
git push origin feature/minha-feature

# 5. Abra um Pull Request detalhando as mudanças
```

> 💡 Siga o padrão [Conventional Commits](https://www.conventionalcommits.org/) para manter o histórico limpo e legível.

<br/>

-----

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo [`LICENSE`](LICENSE) para mais detalhes.

<br/>

-----

<div align="center">

**Construído com ⚡ Vite · ⚛️ React · 🔷 TypeScript**

<br/>

⭐ **Achou útil? Deixa uma estrela e compartilha com a comunidade!** ⭐

<br/>

[![GitHub followers](https://img.shields.io/github/followers/seu-usuario?style=social)](https://github.com/seu-usuario)
[![GitHub stars](https://img.shields.io/github/stars/seu-usuario/forgedev-apps?style=social)](https://github.com/seu-usuario/forgedev-apps)

</div>