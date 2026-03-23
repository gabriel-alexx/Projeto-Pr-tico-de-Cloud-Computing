# ☁️ Projeto Prático de Cloud Computing — Site Estático

Site estático sobre a história do **Nissan Skyline GTR R33**, desenvolvido como projeto prático da disciplina de Cloud Computing. O projeto consiste em uma landing page responsiva com design moderno, hospedada em nuvem.

---

## 🌐 Sobre o Projeto

A página apresenta uma breve história do icônico Nissan Skyline GTR R33 (1995), abordando seus principais diferenciais técnicos: motor, performance, tecnologia e aerodinâmica. O layout foi construído com HTML e CSS puros, sem frameworks externos, com foco em boas práticas de SEO, acessibilidade e responsividade.

---

## ✨ Funcionalidades

- Design responsivo (mobile, tablet e desktop)
- Menu de navegação com suporte a dispositivos móveis (menu hambúrguer)
- Hero section com imagem e descrição do veículo
- Cards informativos com especificações técnicas
- Navegação suave com `scroll-behavior: smooth`
- Ano do rodapé atualizado automaticamente via JavaScript
- Meta tags básicas de SEO e Open Graph

---

## 🗂️ Estrutura do Projeto

```
Projeto-Prático-de-Cloud-Computing-main/
└── index.html   # Página principal (HTML + CSS + JS em arquivo único)
```

---

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — estilização com variáveis CSS, Grid e Flexbox
- **JavaScript** (vanilla) — interatividade do menu mobile e ano dinâmico

> Sem dependências externas ou frameworks. Basta um navegador para rodar.

---

## ▶️ Como rodar localmente

Não é necessário instalar nada. Basta abrir o arquivo diretamente no navegador:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse a pasta
cd Projeto-Prático-de-Cloud-Computing-main

# Abra o arquivo no navegador
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

---

## ☁️ Deploy em Nuvem

Por ser um site estático (apenas HTML/CSS/JS), pode ser hospedado gratuitamente em diversas plataformas de cloud:

| Plataforma | Como fazer o deploy |
|---|---|
| [GitHub Pages](https://pages.github.com/) | Ative nas configurações do repositório > Pages |
| [Netlify](https://netlify.com/) | Arraste a pasta no painel ou conecte o repositório |
| [Vercel](https://vercel.com/) | Importe o repositório pelo painel |
| [AWS S3](https://aws.amazon.com/s3/) | Faça upload do `index.html` e habilite o Static Website Hosting |
| [Azure Static Web Apps](https://azure.microsoft.com/en-us/products/app-service/static) | Conecte o repositório pelo portal do Azure |

---

## 📄 Licença

Desenvolvido por **Gabriel Alexssander Dal Bosco Faria** para fins educacionais.
