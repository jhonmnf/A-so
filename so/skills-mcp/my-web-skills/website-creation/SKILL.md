---
name: website-creation
description: Guia passo a passo para criar um site moderno, do planejamento ao deploy.
---

# Fluxo de Criação de Site

Siga este guia para garantir que o processo de desenvolvimento seja estruturado e profissional.

## 1. Planejamento e Estratégia
- **Definição de Objetivo**: O site é institucional, e-commerce, blog ou landing page?
- **Público-Alvo**: Quem são os usuários? Quais suas dores e necessidades?
- **Mapa do Site (Sitemap)**: Desenhe a hierarquia de páginas (Home $\rightarrow$ Sobre $\rightarrow$ Serviços $\rightarrow$ Contato).
- **Wireframing**: Crie esboços simples da disposição dos elementos (Low-fidelity).

## 2. Design (UI/UX)
- **Identidade Visual**: Defina cores, tipografia e logotipos.
- **Prototipagem**: Crie o design de alta fidelidade no Figma ou Adobe XD.
- **Responsividade**: Planeje como o site se comportará em mobile, tablet e desktop.

## 3. Escolha da Stack Técnica
- **Frontend**: 
  - Simples: HTML/CSS/JS.
  - Moderno: React, Next.js, Vue.js ou Astro.
  - Estilização: Tailwind CSS ou CSS Modules.
- **Backend/CMS**: 
  - Headless CMS: Strapi, Contentful, Sanity.
  - Fullstack: Next.js API Routes, Node.js, Python (FastAPI/Django).
- **Banco de Dados**: PostgreSQL, MongoDB ou Supabase.

## 4. Desenvolvimento
- **Setup**: Inicialize o repositório Git e configure o ambiente de dev.
- **Desenvolvimento Frontend**: Converta o design em código semântico.
- **Integração**: Conecte o frontend às APIs ou ao CMS.
- **Otimização de Imagens**: Use formatos como WebP e compressão adequada.

## 5. Testes e Qualidade
- **Cross-browser**: Teste no Chrome, Firefox, Safari e Edge.
- **Performance**: Use Lighthouse para medir a velocidade de carregamento.
- **QA**: Verifique todos os links, formulários e fluxos de usuário.

## 6. Deploy e Lançamento
- **Hospedagem**: Vercel, Netlify, AWS ou Cloudflare Pages.
- **Domínio**: Configure o DNS e o SSL (HTTPS).
- **Monitoramento**: Adicione Google Analytics ou Plausible para métricas.
