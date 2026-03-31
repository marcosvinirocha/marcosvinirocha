# AGENTS.md

## Visão Geral

Este repositório contém o perfil GitHub de **Marcos Vinicius Oliveira Rocha** - Full Stack Developer baseado em Uberlândia, MG.

## Estrutura do Projeto

### Arquivos Principais

| Arquivo | Descrição |
|---------|-----------|
| `README.md` | Perfil principal do GitHub com estrutura profissional |
| `banner.png` | Banner visual (1200x300px) com gradiente Dracula |
| `banner.html` | Template HTML usado para gerar o banner |

## Estrutura do README.md

### Seções Implementadas

1. **Banner** - Imagem 1200x300px com gradiente Dracula
2. **Bio (Elevator Pitch)** - Introdução focada em SDD e OpenCode
3. **Tech Stack** - Categorizada em Frontend e Backend & DB
4. **GitHub Stats** - Widgets com tema Dracula
5. **Featured Projects** - Tabela com 3 projetos em destaque
6. **Contato** - LinkedIn, Gmail, GitHub com badges
7. **Easter Egg** - Badge Minecraft

### Badges Shields.io

```markdown
### Frontend
React, Next.js, Vue.js, TailwindCSS, TypeScript

### Backend & DB
Java, Spring, Quarkus, Node.js, PostgreSQL
```

## Como Regenerar o Banner

### Pré-requisitos

```bash
npm init -y
npm install puppeteer
```

### Arquivos Temporários

**`generate-banner.js`**
```javascript
const puppeteer = require('puppeteer');
const path = require('path');

async function generateBanner() {
    const browser = await puppeteer.launch({
        headless: 'new',
        args: ['--no-sandbox', '--disable-setuid-sandbox']
    });
    
    const page = await browser.newPage();
    await page.setViewport({ width: 1200, height: 300 });
    
    const htmlPath = path.join(__dirname, 'banner.html');
    await page.goto(`file://${htmlPath}`, { waitUntil: 'networkidle0' });
    
    await page.screenshot({
        path: path.join(__dirname, 'banner.png'),
        clip: { x: 0, y: 0, width: 1200, height: 300 }
    });
    
    await browser.close();
    console.log('Banner gerado: banner.png');
}

generateBanner().catch(console.error);
```

### Execução

```bash
node generate-banner.js
```

### Limpeza

```bash
rm -rf package.json package-lock.json node_modules generate-banner.js
```

## Fluxo de Trabalho para Atualizações

1. **Banner**: Editar `banner.html` → Executar `generate-banner.js` → Commit `banner.png`
2. **README**: Editar `README.md` diretamente → Commit
3. **Badges**: Usar [Shields.io](https://shields.io/) para novos badges
4. **Stats**: Personalizar em [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)

## Links Úteis

- [Shields.io](https://shields.io/) - Badges personalizados
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - Widgets de estatísticas
- [Emojipedia](https://emojipedia.org/) - Emojis para usar

## Informações de Contato

- **Nome**: Marcos Vinicius Oliveira Rocha
- **Localização**: Uberlândia, MG, Brasil
- **Email**: marcosvinicius.udia1256@gmail.com
- **LinkedIn**: [linkedin.com/in/marcosoliveirarocha](https://www.linkedin.com/in/marcosoliveirarocha)
- **GitHub**: [github.com/marcosvinirocha](https://github.com/marcosvinirocha)

## Tecnologias

- **Frontend**: React, Vue.js, Next.js, TailwindCSS, TypeScript
- **Backend**: Java, Spring, Quarkus, Node.js
- **Database**: PostgreSQL
- **Metodologia**: Spec-Driven Development (SDD)
- **Testes**: Vitest, Cypress, JUnit

## Projetos em Destaque

| Projeto | Descrição | Tech Stack |
|---------|-----------|-----------|
| OpenCode | Ferramenta de análise e roast de código com IA | tRPC, Drizzle, AI Agents |
| Smart Inventory | Sistema de controle de estoque industrial | Quarkus, React, Redux |
| Modding KubeJS | Refatoração de receitas para TerraFirmaCraft | JavaScript, Minecraft Forge |
