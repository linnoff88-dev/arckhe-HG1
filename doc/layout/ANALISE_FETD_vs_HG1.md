# 📊 Análise Comparativa: FETD vs HG1

**Data:** 2025-11-23
**Objetivo:** Entender vantagens do padrêo FETD/FEI/FEP e aplicar ao HG1

---

## 🎯 O que o FETD/FEI/FEP tem de MELHOR

### 1. **Homepage com Quiz Interativo**
- ✅ Engaja o usuário imediatamente
- ✅ Personaliza a experiência (descobre qual trilha é ideal)
- ✅ Maior conversêo (usuário nêo fica perdido)
- ✅ Gamificaçêo desde o início

### 2. **Cards de Trilha Mais Simples e Visuais**

**Estrutura FETD:**
```
┌─────────────────────┐
│ 🔵 [Ícone Grande]   │
│ Título da Trilha    │
│ "Slogan motivador"  │
│ ✓ Benefício 1       │
│ ✓ Benefício 2       │
│ ✓ Benefício 3       │
│ [Começar Trilha →]  │
└─────────────────────┘
```

**Estrutura HG1 atual:**
```
┌─────────────────────┐
│ Badge: Módulo 1     │
│ Título              │
│ Descriçêo           │
│ [3 botões]          │
│ Topics expandíveis  │
└─────────────────────┘
```

**Conclusêo:** FETD é mais limpo, visual e direto!

### 3. **Menos Cliques para Conteúdo**
- **FETD:** Homepage → Trilha → Conteúdo (2 cliques)
- **HG1 atual:** Homepage → Tier → Modal/Página → Conteúdo (3+ cliques)

### 4. **Design Mais "Landing Page"**
- Hero com 2 CTAs claros ("Descobrir" e "Ver Todas")
- Seçêo de benefícios/diferenciais
- Foco em conversêo (fazer usuário começar)
- Quiz como elemento de engajamento

### 5. **Estrutura Mais Simples**

**FETD:**
```
/ (homepage com quiz e cards de trilhas)
/trilhas/operacional.html
/trilhas/comunicador.html
/trilhas/talento.html
/trilhas/tecnico.html
```

**HG1 atual:**
```
/ (homepage)
/tiers/tier1.html (landing intermediária)
/docs/tier1/introducao (módulo)
...
```

---

## 🎨 Elementos Visuais FETD

### Paleta de Cores
- **Operacional**: Azul (#3B82F6)
- **Comunicador**: Verde (#10B981)
- **Talento**: Âmbar (#F59E0B)
- **Técnico**: Laranja (#F97316)

### Tipografia
- **Fonte:** Inter (Google Fonts)
- **Fallbacks:** -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, sans-serif

### Animações
- Transições suaves em cores/bordas (200ms ease-in-out)
- Hover em cards: translateY(-2px) + sombra
- Fade-in no carregamento

### Cards de Trilha
**Elementos:**
1. Ícone circular colorido (grande)
2. Título em negrito
3. Slogan entre aspas (itálico)
4. Descriçêo do público-alvo
5. Lista de 4 benefícios com ✓
6. Botêo CTA com seta →

---

## 💡 Decisêo para HG1

### **Opçêo Escolhida: Adaptar Homepage para padrêo FETD**

**Mudanças:**
1. ✅ **Homepage:** Adicionar quiz "Qual tier começar?" (3 perguntas)
2. ✅ **Hero Section:** Estilo FETD com 2 CTAs
3. ✅ **Cards dos Tiers:** Simplificar no estilo FETD (ícone grande + checkmarks)
4. ✅ **Remover:** Páginas `/tiers/tierX.html` intermediárias
5. ✅ **Estrutura direta:** Homepage → Docs do Tier

**Vantagens:**
- ✅ Menos cliques para conteúdo
- ✅ Quiz ajuda usuário a escolher tier certo
- ✅ Mais engajamento
- ✅ Design mais moderno e limpo
- ✅ Menor manutençêo (menos páginas)

---

## 🎯 Nova Estrutura Homepage HG1

```
┌─────────────────────────────────────┐
│ Navbar sticky (dark mode toggle)    │
├─────────────────────────────────────┤
│ HERO SECTION                        │
│ 🤖 Academia de Humanoides           │
│ "Domine Robôs Humanoides"          │
│ [Descobrir Meu Tier] [Ver Tiers]   │
├─────────────────────────────────────┤
│ SEÇêO DE BENEFÍCIOS                 │
│ 4 cards: Gratuito, Open Source,    │
│ Prático, Progressivo                │
├─────────────────────────────────────┤
│ QUIZ INTERATIVO                     │
│ "Qual tier é ideal para você?"      │
│ Pergunta 1/3                        │
│ [ ] Nunca vi um robô humanóide     │
│ [ ] Já sei o básico                │
│ [ ] Quero programar                │
├─────────────────────────────────────┤
│ CARDS DOS 3 TIERS                   │
│ ┌──────────┐ ┌──────────┐ ┌───────┐│
│ │ 🔵       │ │ 🟣       │ │ 🟢    ││
│ │ Tier 1   │ │ Tier 2   │ │ Tier 3││
│ │ "Fundame"│ │ "Operaçêo│ │ "Prog"││
│ │ ✓ O que  │ │ ✓ Contro │ │ ✓ Pyth││
│ │ ✓ Histór │ │ ✓ Seguran│ │ ✓ ROS2││
│ │ ✓ Models │ │ ✓ Manutn │ │ ✓ IA  ││
│ │ ✓ Aplica │ │ ✓ Simula │ │ ✓ Auto││
│ │ [Começar→│ │ [Começar→│ │[Começ→││
│ └──────────┘ └──────────┘ └───────┘│
├─────────────────────────────────────┤
│ Footer (3 colunas)                  │
└─────────────────────────────────────┘
```

---

## 📁 Arquivos a Modificar

### Criar/Modificar:
1. `src/pages/index.tsx` - Homepage FETD style
2. `src/css/custom.css` - Estilos adicionais
3. `static/js/quiz.js` - Lógica do quiz (se necessário)

### Remover:
1. `static/tiers/tier1.html` (nêo mais necessário)
2. `static/tiers/tier2.html` (se existir)
3. `static/tiers/tier3.html` (se existir)

### Manter:
1. `docs/tier1/introducao.mdx` - Conteúdo dos módulos
2. `docusaurus.config.ts` - Configuraçêo
3. Estrutura de docs existente

---

## 🎨 Sistema de Cores HG1 (adaptado de FETD)

```javascript
colors: {
  'tier-1': '#3B82F6',    // Azul (Fundamentos)
  'tier-2': '#9b59b6',    // Roxo (Operaçêo)
  'tier-3': '#10B981',    // Verde (Programaçêo)
  'success': '#22C55E',
  'warning': '#F59E0B',
  'error': '#EF4444',
}
```

---

## ✅ Implementaçêo

**Status:** Aprovado
**Próximo passo:** Refazer homepage no estilo FETD
**Mantém:** Docusaurus para módulos (MDX)
**Remove:** Páginas tier intermediárias (HTML estático)

---

**Criado por:** Claude Code
**Projeto:** HG1 - Academia de Humanoides
**Baseado em:** FETD, FEI, FEP (linnoff88-dev.github.io)
