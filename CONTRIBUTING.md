# Guia de Contribuiçêo

Obrigado por considerar contribuir com a Academia de Humanoides! 🎉

## 🌟 Como Contribuir

### Reportar Bugs

Se você encontrou um bug, por favor [abra uma issue](https://github.com/nmaldaner/MindON/issues/new) com:

- Descriçêo clara do problema
- Passos para reproduzir
- Comportamento esperado vs. atual
- Screenshots (se aplicável)
- Ambiente (navegador, OS, versêo do Node)

### Sugerir Melhorias

Tem uma ideia para melhorar a plataforma? [Abra uma issue](https://github.com/nmaldaner/MindON/issues/new) descrevendo:

- Qual problema você está tentando resolver?
- Qual é sua soluçêo proposta?
- Alternativas que você considerou

### Contribuir com Código

1. **Fork o Repositório**
   ```bash
   git clone https://github.com/seu-usuario/MindON.git
   cd MindON
   ```

2. **Crie uma Branch**
   ```bash
   git checkout -b feature/sua-feature
   # ou
   git checkout -b fix/seu-bug
   ```

3. **Instale Dependências**
   ```bash
   pnpm install
   ```

4. **Faça suas Mudanças**
   - Siga os [padrões de código](#padrões-de-código)
   - Adicione testes se necessário
   - Atualize documentaçêo se necessário

5. **Teste suas Mudanças**
   ```bash
   pnpm lint          # Verifica linting
   pnpm test          # Executa testes
   pnpm build         # Verifica se build funciona
   ```

6. **Commit suas Mudanças**
   ```bash
   git commit -m "feat: adiciona nova funcionalidade X"
   ```

   Usamos [Conventional Commits](https://www.conventionalcommits.org/):
   - `feat:` Nova funcionalidade
   - `fix:` Correçêo de bug
   - `docs:` Mudanças na documentaçêo
   - `style:` Formataçêo, sem mudança de código
   - `refactor:` Refatoraçêo de código
   - `test:` Adiçêo ou correçêo de testes
   - `chore:` Tarefas de manutençêo

7. **Push e Crie Pull Request**
   ```bash
   git push origin feature/sua-feature
   ```

   Depois, [crie um Pull Request](https://github.com/nmaldaner/MindON/compare) descrevendo suas mudanças.

### Contribuir com Conteúdo

Você pode melhorar o conteúdo educacional:

1. **Editar Módulos Existentes**
   - Arquivos MDX em `docs/tier1/`, `docs/tier2/`, `docs/tier3/`
   - Corrija erros, melhore explicações, adicione exemplos

2. **Adicionar Novos Recursos**
   - Diagramas em `static/img/diagrams/`
   - Exemplos de código em `static/code-examples/`

3. **Melhorar Glossário**
   - Edite `docs/glossary.mdx`
   - Adicione novos termos técnicos

### Padrões de Código

#### TypeScript/React
- Use TypeScript (sem `any`)
- Componentes funcionais com hooks
- Props tipadas com interfaces
- Nomes em PascalCase para componentes
- Nomes em camelCase para variáveis/funções

#### Styling
- Prefer Tailwind utilities
- Use CSS Modules para estilos complexos
- Siga dark mode (teste em ambos os temas)

#### Acessibilidade
- Todos elementos interativos devem ser acessíveis via teclado
- Use ARIA labels apropriados
- Mantenha contraste 4.5:1 (WCAG AA)

#### Documentaçêo
- Documente componentes com JSDoc
- README atualizado para novas features
- Exemplos de uso para componentes

## 🧪 Testes

```bash
# Executa todos os testes
pnpm test

# Testes em watch mode
pnpm test:watch

# Cobertura de testes
pnpm test:coverage
```

Aim for 80%+ coverage em componentes e utils.

## 📦 Build & Deploy

O build é feito automaticamente via GitHub Actions ao fazer merge na branch `main`.

Para testar build localmente:

```bash
pnpm build
pnpm serve
```

## 🤔 Dúvidas?

- [Abra uma issue](https://github.com/nmaldaner/MindON/issues/new)
- [Participe do Discord](https://discord.gg/humanoides)

## 📜 Código de Conduta

Este projeto segue o [Contributor Covenant](https://www.contributor-covenant.org/). Ao participar, você concorda em seguir este código.

---

**Obrigado por contribuir!** 🙏
