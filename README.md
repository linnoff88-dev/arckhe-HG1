# ê°Å¸Â¤â Academia de Humanoides (HG1)

> **Domine RobêÂ´s Humanoides do Zero ao AvanêÂ§ado**
> Plataforma educacional 100% gratuita e open-source sobre robêÂ³tica humanoide

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Built with Docusaurus](https://img.shields.io/badge/Built%20with-Docusaurus%203-brightgreen.svg)](https://docusaurus.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.3-blue.svg)](https://www.typescriptlang.org/)
[![Deploy Status](https://github.com/linnoff88-dev/HG1/actions/workflows/deploy.yml/badge.svg)](https://github.com/linnoff88-dev/HG1/actions)

ê°Å¸ÅÂ **[Acesse o site](https://linnoff88-dev.github.io/

---

## ê°Å¸âÅ¡ Sobre o Projeto

A **Academia de Humanoides (HG1)** êÂ© uma jornada de aprendizagem progressiva sobre robêÂ´s humanoides, desde fundamentos teêÂ³ricos atêÂ© programaêÂ§êÂ£o avanêÂ§ada com ROS2 e IA.

Inspirada no padrêÂ£o **FETD (FormaêÂ§êÂ£o em Engenharia de Tecnologia Digital)**, a plataforma oferece:

- ê¢Åâ¦ **100% Gratuito** - Todo conteêÂºdo livre e acessêÂ­vel
- ê¢Åâ¦ **Open Source** - CêÂ³digo aberto no GitHub
- ê¢Åâ¦ **Progressivo** - Do bêÂ¡sico ao avanêÂ§ado, passo a passo
- ê¢Åâ¦ **PrêÂ¡tico** - AplicaêÂ§êÂµes reais, simuladores e exemplos de cêÂ³digo
- ê¢Åâ¦ **Atualizado** - ConteêÂºdo sobre modelos 2024 (Tesla Optimus, Unitree H1, Figure 02)

---

## ê°Å¸Å½Â¯ Estrutura de Aprendizagem

### ê°Å¸âÂµ **Tier 1: Conhecendo Humanoides** (Fundamentos)

**10 mêÂ³dulos completos** explorando os fundamentos da robêÂ³tica humanoide:

| # | MêÂ³dulo | Tempo | ConteêÂºdo |
|---|--------|-------|----------|
| 1 | ê°Å¸Â¤â IntroduêÂ§êÂ£o aos Humanoides | 10 min | O que sêÂ£o, histêÂ³ria, aplicaêÂ§êÂµes |
| 2 | ê°Å¸âÅ HistêÂ³ria e EvoluêÂ§êÂ£o | 15 min | WABOT-1 atêÂ© Tesla Optimus (2024) |
| 3 | ê°Å¸Â¤â Principais Modelos | 20 min | Unitree H1, Optimus, Figure 02, Atlas |
| 4 | ê°Å¸Å½Â¯ Sensores | 18 min | CêÂ¢meras, LIDAR, IMU, forêÂ§a, e-skin |
| 5 | ê°Å¸Â¦Â¾ Atuadores e Controle | 20 min | Servos, QDD, hidrêÂ¡ulica, controle de torque |
| 6 | ê°Å¸âÂ» ComputaêÂ§êÂ£o Embarcada | 16 min | Jetson, MCU, CANbus, arquitetura |
| 7 | ê°Å¸ââ¹ Energia e Bateria | 14 min | Li-Ion, LFP, BMS, autonomia |
| 8 | ê°Å¸Â§Â  Software e IA | 22 min | ROS2, RL, LLMs, SLAM, visêÂ£o |
| 9 | ê°Å¸ÂÂ­ AplicaêÂ§êÂµes PrêÂ¡ticas | 16 min | Tesla, BMW, Amazon (casos reais) |
| 10 | ê°Å¸âÂ® O Futuro dos Humanoides | 18 min | ProjeêÂ§êÂµes 2025-2050 |

**Total:** ~3 horas de conteêÂºdo rico com tabs interativos, tabelas comparativas e exemplos de cêÂ³digo.

---

### ê°Å¸Å¸Â£ **Tier 2: Operando Humanoides** (Em breve)

Aprenda a controlar robêÂ´s humanoides:
- Interfaces de controle e telemetria
- SeguranêÂ§a e melhores prêÂ¡ticas
- CalibraêÂ§êÂ£o e manutenêÂ§êÂ£o
- Simuladores virtuais (Gazebo, Isaac Sim)

---

### ê°Å¸Å¸Â¢ **Tier 3: Programando Humanoides** (Em breve)

ProgramaêÂ§êÂ£o avanêÂ§ada:
- Python para robêÂ³tica
- ROS2 e frameworks
- VisêÂ£o computacional e IA
- NavegaêÂ§êÂ£o autêÂ´noma e manipulaêÂ§êÂ£o

---

## ê°Å¸Å¡â¬ Quick Start - Desenvolvimento Local

### PrêÂ©-requisitos

```bash
Node.js 18.0+
pnpm 8.0+
```

### InstalaêÂ§êÂ£o

```bash
# Clone o repositêÂ³rio
git clone https://github.com/linnoff88-dev/HG1.git
cd HG1

# Instale as dependêÂªncias
pnpm install

# Inicie o servidor de desenvolvimento
pnpm start
```

O site estarêÂ¡ disponêÂ­vel em **`http://localhost:3000/HG1/`**

### Build para ProduêÂ§êÂ£o

```bash
# Gera build estêÂ¡tico
pnpm build

# Serve o build localmente
pnpm serve
```

---

## ê°Å¸âÂ Estrutura do Projeto

```
HG1/
ê¢âÅê¢ââ¬ê¢ââ¬ docs/                       # ConteêÂºdo educacional (MDX)
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ tier1/                 # ê¢Åâ¦ 10 mêÂ³dulos completos
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ introducao.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 02-historia.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 03-modelos.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 04-sensores.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 05-atuadores.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 06-computacao.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 07-energia.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 08-software.mdx
ê¢ââ   ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ 09-aplicacoes.mdx
ê¢ââ   ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ 10-futuro.mdx
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ tier2/                 # ê°Å¸âÅ Em desenvolvimento
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ tier3/                 # ê°Å¸âÅ Roadmap planejado
ê¢âÅê¢ââ¬ê¢ââ¬ src/
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ components/            # Componentes React customizados
ê¢ââ   ê¢âÅê¢ââ¬ê¢ââ¬ pages/
ê¢ââ   ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ index.tsx          # Homepage com quiz interativo
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ css/
ê¢ââ       ê¢âÅê¢ââ¬ê¢ââ¬ custom.css         # Estilos customizados
ê¢ââ       ê¢ââê¢ââ¬ê¢ââ¬ tier-pages.css     # Estilos especêÂ­ficos dos tiers
ê¢âÅê¢ââ¬ê¢ââ¬ static/                    # Assets estêÂ¡ticos
ê¢âÅê¢ââ¬ê¢ââ¬ .github/
ê¢ââ   ê¢ââê¢ââ¬ê¢ââ¬ workflows/
ê¢ââ       ê¢ââê¢ââ¬ê¢ââ¬ deploy.yml         # CI/CD para GitHub Pages
ê¢âÅê¢ââ¬ê¢ââ¬ docusaurus.config.ts       # ConfiguraêÂ§êÂ£o principal
ê¢ââê¢ââ¬ê¢ââ¬ sidebars.ts                # NavegaêÂ§êÂ£o lateral
```

---

## ê°Å¸âºÂ ê¯Â¸Â Tech Stack

| Categoria | Tecnologia |
|-----------|-----------|
| **Framework** | [Docusaurus 3.5.2](https://docusaurus.io/) |
| **Linguagem** | [TypeScript 5.3](https://www.typescriptlang.org/) |
| **Styling** | CSS Modules + Infima |
| **Deployment** | GitHub Pages (Actions) |
| **Package Manager** | pnpm 8 |
| **Content** | MDX (Markdown + React) |

---

## ê°Å¸Å½Â¨ Design e UX

### PadrêÂ£o FETD/FEI

O projeto segue o padrêÂ£o de design FETD (FormaêÂ§êÂ£o em Engenharia de Tecnologia Digital):

- **Homepage Interativa:** Quiz de 3 perguntas que recomenda o tier ideal
- **Cards Visuais:** Grandes êÂ­cones, slogans motivadores, benefêÂ­cios claros
- **NavegaêÂ§êÂ£o Direta:** Homepage ê¢â â ConteêÂºdo (mêÂ¡ximo 2 cliques)
- **Sistema de Cores:**
  - ê°Å¸âÂµ Tier 1: Azul `#3B82F6`
  - ê°Å¸Å¸Â£ Tier 2: Roxo `#9b59b6`
  - ê°Å¸Å¸Â¢ Tier 3: Verde `#10B981`

### Componentes Interativos

- ê¢Åâ¦ Tabs (comparaêÂ§êÂµes lado a lado)
- ê¢Åâ¦ Tabelas responsivas
- ê¢Åâ¦ Callouts (tips, info, warnings)
- ê¢Åâ¦ Code blocks com syntax highlighting
- ê¢Åâ¦ Quiz interativo com estado local

---

## ê°Å¸âÅ Scripts DisponêÂ­veis

```bash
pnpm start          # Servidor de desenvolvimento (localhost:3000)
pnpm build          # Build para produêÂ§êÂ£o (output: ./build)
pnpm serve          # Serve build localmente
pnpm clear          # Limpa cache do Docusaurus
pnpm swizzle        # Customiza componentes Docusaurus
pnpm deploy         # Deploy manual (use GitHub Actions)
```

---

## ê°Å¸ÅÂ Deploy e CI/CD

### AutomêÂ¡tico via GitHub Actions

Cada `git push` na branch `main` dispara:

1. ê¢Åâ¦ Build do Docusaurus
2. ê¢Åâ¦ Testes de compilaêÂ§êÂ£o
3. ê¢Åâ¦ Deploy para GitHub Pages

**Workflow:** `.github/workflows/deploy.yml`

### ConfiguraêÂ§êÂ£o do GitHub Pages

1. VêÂ¡ em **Settings** ê¢â â **Pages**
2. Source: **GitHub Actions**
3. URL: `https://linnoff88-dev.github.io/

---

## ê°Å¸âÅ  EstatêÂ­sticas do Projeto

```
ê°Å¸ââ Arquivos MDX: 10 mêÂ³dulos Tier 1
ê°Å¸âÂ Linhas de cêÂ³digo: ~6,000 (conteêÂºdo educacional)
ê¢ÂÂ±ê¯Â¸Â Tempo de leitura: ~3 horas (Tier 1)
ê°Å¸Å½Â¯ MêÂ³dulos planejados: 25+ (todos os tiers)
ê°Å¸âÂ¦ Tamanho do build: ~8 MB
ê°Å¸Å¡â¬ Performance: 95+ (Lighthouse)
```

---

## ê°Å¸Â¤Â Contribuindo

ContribuiêÂ§êÂµes sêÂ£o muito bem-vindas! Para contribuir:

1. **Fork** o repositêÂ³rio
2. Crie uma **branch** para sua feature (`git checkout -b feature/MinhaFeature`)
3. **Commit** suas mudanêÂ§as (`git commit -m 'feat: adiciona nova seêÂ§êÂ£o sobre sensores'`)
4. **Push** para a branch (`git push origin feature/MinhaFeature`)
5. Abra um **Pull Request**

### Guidelines

- Use commits semêÂ¢nticos (feat, fix, docs, style, refactor, test, chore)
- MDX: Siga o padrêÂ£o dos mêÂ³dulos existentes (tabs, callouts, code blocks)
- Imagens: Otimize antes de adicionar (< 200KB)
- Links: Sempre use HTTPS

---

## ê°Å¸ââ LicenêÂ§a

Este projeto estêÂ¡ licenciado sob a **LicenêÂ§a MIT** - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## ê°Å¸â¢Â Agradecimentos e ReferêÂªncias

### Projetos que Inspiraram

- **FETD, FEI, FEP** - PadrêÂ£o de design e estrutura de cursos (linnoff88-dev.github.io)
- **Unitree Robotics** - DocumentaêÂ§êÂ£o têÂ©cnica e especificaêÂ§êÂµes
- **Boston Dynamics** - VêÂ­deos e materiais educacionais
- **Tesla AI** - Blog e updates sobre Optimus

### Comunidade

- [r/robotics](https://reddit.com/r/robotics) - DiscussêÂµes e novidades
- [ROS Discourse](https://discourse.ros.org/) - Comunidade ROS2
- [Unitree Community](https://www.unitree.com/community) - FêÂ³rum oficial

---

## ê°Å¸âÅ¾ Contato

- **GitHub Issues:** [Reporte bugs ou sugira features](https://github.com/linnoff88-dev/HG1/issues)
- **Discussions:** [Perguntas e discussêÂµes](https://github.com/linnoff88-dev/HG1/discussions)
- **Email:** [nmaldaner@example.com](mailto:nmaldaner@example.com)

---

## ê°Å¸âÂºê¯Â¸Â Roadmap

- [x] **Q4 2024:** Tier 1 completo (10 mêÂ³dulos)
- [ ] **Q1 2025:** Tier 2 - OperaêÂ§êÂ£o e Simuladores
- [ ] **Q2 2025:** Tier 3 - ProgramaêÂ§êÂ£o ROS2
- [ ] **Q3 2025:** Projetos prêÂ¡ticos e certificados
- [ ] **Q4 2025:** IntegraêÂ§êÂ£o com simuladores online

---

<div align="center">

**ê°Å¸Â¤â Feito com ê¢ÂÂ¤ê¯Â¸Â pela comunidade de robêÂ³tica**

[ê°Å¸ÅÅ¸ Star no GitHub](https://github.com/linnoff88-dev/HG1) ê¢â¬Â¢ [ê°Å¸Ââº Reportar Bug](https://github.com/linnoff88-dev/HG1/issues) ê¢â¬Â¢ [ê°Å¸âÂ¡ Sugerir Feature](https://github.com/linnoff88-dev/HG1/issues/new)

</div>

---

Projeto adaptado da comunidade ARCKHê TDS - ARCKHÉe