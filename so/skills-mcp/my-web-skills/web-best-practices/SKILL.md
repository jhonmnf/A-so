---
name: web-best-practices
description: Check-list de melhores práticas para performance, SEO, acessibilidade e segurança.
---

# Melhores Práticas para Desenvolvimento Web

Utilize este check-list para garantir que o site seja de alta qualidade e competitivo.

## 🚀 Performance (Velocidade)
- [ ] **Core Web Vitals**: Otimize LCP (Largest Contentful Paint), FID (First Input Delay) e CLS (Cumulative Layout Shift).
- [ ] **Lazy Loading**: Implemente carregamento tardio para imagens e iframes fora da tela.
- [ ] **Minificação**: Minifique arquivos CSS e JS para reduzir o tamanho do payload.
- [ ] **Caching**: Configure cache de navegador e utilize CDNs para arquivos estáticos.
- [ ] **Imagens Otimizadas**: Use formatos modernos (WebP, AVIF) e dimensões adequadas para cada tela.

## 🔍 SEO (Search Engine Optimization)
- [ ] **HTML Semântico**: Use tags como `<header>`, `<main>`, `<footer>`, `<article>` e `<h1>`-`<h6>` corretamente.
- [ ] **Meta Tags**: Configure corretamente `<title>`, `<meta description>` e tags Open Graph para redes sociais.
- [ ] **URLs Amigáveis**: Use slugs descritivos (ex: `/servicos/criacao-de-sites` em vez de `/page.php?id=123`).
- [ ] **Sitemap e Robots.txt**: Crie e envie o sitemap.xml para o Google Search Console.
- [ ] **Alt Text**: Adicione descrições significativas a todas as imagens.

## ♿ Acessibilidade (a11y)
- [ ] **Contraste de Cores**: Garanta que o contraste entre texto e fundo atenda aos padrões WCAG.
- [ ] **Navegação por Teclado**: Certifique-se de que todo o site seja navegável via tecla Tab.
- [ ] **ARIA Roles**: Use atributos `aria-label` e `role` onde a semântica do HTML não for suficiente.
- [ ] **Foco Visível**: Mantenha o indicador de foco (outline) visível para usuários de teclado.

## 🛡️ Segurança
- [ ] **HTTPS**: Certificado SSL instalado e forçando redirecionamento de HTTP para HTTPS.
- [ ] **Sanitização de Input**: Proteja contra XSS (Cross-Site Scripting) e SQL Injection.
- [ ] **Content Security Policy (CSP)**: Implemente headers de segurança para evitar a execução de scripts maliciosos.
- [ ] **Dependências Atualizadas**: Use `npm audit` ou Snyk para monitorar vulnerabilidades em bibliotecas externas.

## 📱 Experiência do Usuário (UX)
- [ ] **Mobile-First**: Desenvolva primeiro para telas pequenas e expanda para telas maiores.
- [ ] **Feedback Visual**: Adicione estados de hover, active e loading para interações do usuário.
- [ ] **Hierarquia Visual**: Use tipografia e espaços em branco para guiar a atenção do usuário.
