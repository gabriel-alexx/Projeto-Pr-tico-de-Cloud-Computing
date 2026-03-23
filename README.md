# ☁️ Projeto Prático de Cloud Computing — Site Estático

**Projeto Integrador — Cloud Computing**  
👤 Autor: Gabriel Alexssander Dal Bosco Faria  
🌐 Deploy: [projeto-cloud.netlify.app](https://projeto-cloud.netlify.app)

---

## 📖 Sobre o Projeto

Site estático sobre a história do **Nissan Skyline GTR R33**, desenvolvido como projeto prático da disciplina de Cloud Computing. O projeto consiste em uma landing page responsiva com design moderno, hospedada no **Netlify** via integração com o GitHub.

A página foi construída como um **único arquivo HTML** (`index.html`), com HTML, CSS e JavaScript integrados — sem necessidade de build ou backend.

---

## 🗂️ Estrutura do Projeto

```
Projeto-Prático-de-Cloud-Computing-main/
└── index.html   # Página principal (HTML + CSS + JS em arquivo único)
```

### Organização interna do arquivo

| Camada | Localização | Função |
|---|---|---|
| **HTML** | Estrutura do documento | Seções e semântica da página |
| **CSS** | Tag `<style>` | Estilos visuais, responsividade e variáveis |
| **JavaScript** | Tag `<script>` | Menu mobile e ano dinâmico no rodapé |

---

## ✨ Funcionalidades

**Layout (seções da página):**
- **Header fixo (sticky)** — logo, menu de navegação e botão de ação
- **Hero** — título, subtítulo, botões de ação e imagem ilustrativa
- **Seção de Recursos** — cards com ícones e especificações técnicas do GTR R33
- **Footer** — direitos autorais e botão "Voltar ao topo"

**CSS:**
- Design moderno com cores escuras, gradientes azul/ciano e sombras suaves
- Componentes reutilizáveis: `card`, `cta` (botão principal), `ghost` (botão secundário)
- Grid responsivo: 2 colunas no Hero e 3 nos Recursos no desktop; 1 coluna no mobile
- Menu hambúrguer para telas menores

**JavaScript:**
- Ano automático no rodapé via `new Date().getFullYear()`
- Menu mobile acessível com abertura/fechamento e atributo `aria-expanded`

**Cabeçalho (`<head>`):**
- Meta tags de SEO (descrição, título, Open Graph)
- Responsividade via viewport
- Variáveis CSS em `:root` para fácil personalização

**Acessibilidade:**
- Atributos `aria-label`, `aria-expanded` e `role` para leitores de tela
- Contraste de cores adequado
- Foco visível em links e botões

---

## 🔄 Fluxo de Navegação

```
[Header - Menu fixo]
        │
        ▼
   [Hero / Topo]
        │
        ▼
[Seção de Recursos]
        │
        ▼
    [Footer]
        │
        ▼
[← Voltar ao topo]
```

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — variáveis CSS, Grid, Flexbox e media queries
- **JavaScript** (vanilla) — interatividade leve, sem dependências

> Sem frameworks ou dependências externas. Basta um navegador para rodar.

---

## ▶️ Como rodar localmente

```bash
# Clone o repositório
git clone https://github.com/gabriel-alexx/Projeto-Pr-tico-de-Cloud-Computing.git

# Acesse a pasta
cd Projeto-Pr-tico-de-Cloud-Computing

# Abra no navegador
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

---

## ☁️ Deploy — Publicando no GitHub e Netlify

### 1. Configurando o Git e enviando para o GitHub

```bash
# Inicializar o repositório
git init

# Adicionar os arquivos ao staging
git add .

# Fazer o primeiro commit
git commit -m "Primeiro commit"

# Garantir que a branch se chama main
git branch -M main

# Conectar ao repositório remoto
git remote add origin https://github.com/gabriel-alexx/Projeto-Pr-tico-de-Cloud-Computing.git

# Caso o remote já exista, atualize a URL
git remote set-url origin https://github.com/gabriel-alexx/Projeto-Pr-tico-de-Cloud-Computing.git

# Enviar para o GitHub
git push -u origin main
```

> 💡 Faça o download do Git em: https://git-scm.com/downloads

### 2. Hospedando no Netlify

1. Acesse [app.netlify.com](https://app.netlify.com) e crie uma conta
2. Conecte com o GitHub **ou** faça upload da pasta diretamente (drag & drop)
3. Selecione o repositório e configure o nome do site
4. Após o deploy, o site ficará disponível na URL escolhida

🔗 Site publicado: **[projeto-cloud.netlify.app](https://projeto-cloud.netlify.app)**

---

## 🎨 Personalização

| O que mudar | Onde |
|---|---|
| Nome da marca | Substituir `"Skyline GTR R33"` nos textos |
| Cores principais | Variáveis `--brand` e `--brand-2` no `:root` do CSS |
| Imagens | URLs na seção Hero e demais seções |
| Formulário de contato | Integrar com **Formspree**, **Netlify Forms** ou backend próprio |

---

## 📄 Licença

Desenvolvido por **Gabriel Alexssander Dal Bosco Faria** para fins educacionais — Projeto Integrador de Cloud Computing.
