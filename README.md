# Cuiabá Digital

**Plataforma de Turismo, Cultura e Natureza em Cuiabá, Mato Grosso**

Uma iniciativa acadêmica com propósito de impacto social, cultural e econômico, desenvolvida com HTML e CSS puros.

---

## 📋 Visão Geral do Projeto

O **Cuiabá Digital** é um site completo e responsivo que apresenta e valoriza as experiências locais de Cuiabá através de três pilares principais:

- **🍽️ Turismo Gastronômico** — Rota do Peixe, Maria Isabel, Ventrecha de Pacu
- **🎭 Economia Criativa** — Artesanato, Siriri, Cururu, eventos culturais
- **🌿 Natureza & Lazer** — Parques urbanos, Chapada dos Guimarães, trilhas

---

## 🎯 Objetivo

Conectar turistas e moradores a experiências autênticas em Cuiabá, valorizando a identidade cultural, gastronômica e natural, enquanto impulsiona a economia criativa e o turismo sustentável.

---

## 📁 Estrutura de Pastas

```
cuiaba-digital/
├── index.html                 # Página inicial
├── css/
│   └── style.css             # Estilos globais (responsivo)
├── pages/
│   ├── gastronomia.html      # Turismo Gastronômico
│   ├── cultura.html          # Economia Criativa
│   ├── natureza.html         # Natureza & Lazer
│   ├── sobre.html            # Sobre o Projeto
│   └── contato.html          # Formulário de Contato
├── assets/
│   ├── images/               # Pasta para imagens
│   └── icons/                # Pasta para ícones
└── README.md                 # Este arquivo
```

---

## 🚀 Como Usar

### 1. Abrir o Site Localmente

**Opção 1: Abrir diretamente no navegador**
- Localize o arquivo `index.html` na pasta do projeto
- Clique duas vezes para abrir no navegador padrão

**Opção 2: Usar um servidor local (recomendado)**

Com Python 3:
```bash
cd cuiaba-digital
python3 -m http.server 8000
```

Depois acesse: `http://localhost:8000`

Com Node.js (http-server):
```bash
cd cuiaba-digital
npx http-server
```

### 2. Navegar pelo Site

- **Início** — Página principal com apresentação dos 3 pilares
- **Gastronomia** — Explore a Rota do Peixe e pratos típicos
- **Cultura** — Conheça artesanato, Siriri, Cururu e eventos
- **Natureza** — Descubra parques e a Chapada dos Guimarães
- **Sobre** — Entenda a missão e impacto do projeto
- **Contato** — Envie mensagens e sugestões

---

## 🎨 Design e Identidade Visual

### Paleta de Cores

| Cor | Código | Uso |
|-----|--------|-----|
| Laranja Primário | `#FF6B1A` | Destaque, botões, links |
| Âmbar | `#E8A020` | Secundário, gradientes |
| Verde Regional | `#328C50` | Natureza, elementos terciários |
| Teal | `#1A8C8C` | Acentos, variações |
| Marrom | `#5C3D2E` | Neutro, textos |

### Tipografia

- **Headings:** Segoe UI, sans-serif (bold)
- **Body:** Segoe UI, sans-serif (regular)
- **Tamanhos:** Responsivos, adaptados para mobile e desktop

### Componentes Principais

- **Header Sticky** — Navegação fixa com menu responsivo
- **Hero Sections** — Banners atraentes com gradientes
- **Cards** — Componentes reutilizáveis com hover effects
- **Formulário** — Contato funcional com validação básica
- **Footer** — Informações e links de navegação

---

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:

- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (até 767px)

Breakpoints principais:
- `@media (max-width: 768px)` — Ajustes para tablets
- `@media (max-width: 480px)` — Otimizações para mobile

---

## ✨ Recursos e Funcionalidades

### HTML Semântico

- Uso correto de tags `<header>`, `<main>`, `<section>`, `<footer>`
- Estrutura acessível com atributos ARIA quando necessário
- Meta tags para SEO e responsividade

### CSS Moderno

- **Flexbox e Grid** — Layouts flexíveis e responsivos
- **Variáveis CSS** — Fácil manutenção de cores e espaçamentos
- **Transições e Hover Effects** — Interatividade suave
- **Gradientes** — Design moderno e atrativo
- **Sombras** — Profundidade visual

### JavaScript Funcional

- **Menu Mobile** — Toggle responsivo
- **Formulário de Contato** — Validação e feedback ao usuário
- **Smooth Scroll** — Navegação suave entre seções

---

## 🔧 Customização

### Alterar Cores

Edite o arquivo `css/style.css` e modifique as variáveis CSS no `:root`:

```css
:root {
  --primary-orange: #FF6B1A;
  --primary-amber: #E8A020;
  --primary-green: #328C50;
  /* ... */
}
```

### Adicionar Novas Páginas

1. Crie um novo arquivo HTML em `pages/`
2. Copie a estrutura de uma página existente
3. Atualize o menu de navegação em `header`
4. Mantenha o mesmo `link` para o CSS

### Adicionar Imagens

1. Coloque imagens em `assets/images/`
2. Referencie no HTML: `<img src="../assets/images/nome.jpg" alt="descrição">`

---

## 📊 Páginas e Conteúdo

### 1. **index.html** — Página Inicial
- Apresentação do projeto
- Destaque dos 3 pilares
- Cards de destaques
- Chamada para ação

### 2. **gastronomia.html** — Turismo Gastronômico
- Informações sobre a Rota do Peixe
- 6 pratos típicos com descrições
- Dicas de visita
- Experiência gastronômica

### 3. **cultura.html** — Economia Criativa
- Artesanato regional
- 5 manifestações culturais (Siriri, Cururu, etc.)
- Calendário de eventos
- Apoio aos criadores locais

### 4. **natureza.html** — Natureza & Lazer
- Parques urbanos
- 6 atrativos naturais principais
- Informações sobre Chapada dos Guimarães
- Dicas de segurança
- Biodiversidade local

### 5. **sobre.html** — Sobre o Projeto
- Propósito e contexto acadêmico
- Missão, visão e valores
- Impacto esperado
- Públicos-alvo
- Compromissos

### 6. **contato.html** — Contato
- Formulário funcional
- Informações de contato
- Tipos de contato
- FAQ com 6 perguntas frequentes

---

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como uma atividade acadêmica com foco em:

- **Design Web** — Identidade visual e UX/UI
- **Desenvolvimento Frontend** — HTML e CSS puros
- **Responsividade** — Mobile-first approach
- **Semântica** — Estrutura HTML correta
- **Conteúdo** — Pesquisa e redação estratégica

---

## 💡 Diferenciais Implementados

✅ **Menu Mobile Responsivo** — Funciona perfeitamente em celulares

✅ **Formulário de Contato** — Com validação e feedback visual

✅ **Hover Effects** — Transições suaves e interatividade

✅ **Gradientes Temáticos** — Identidade visual regional

✅ **Cards Interativos** — Elevação e transformação ao passar o mouse

✅ **Estrutura Semântica** — HTML5 correto e acessível

✅ **Variáveis CSS** — Fácil manutenção e consistência

✅ **Documentação Completa** — README detalhado

---

## 🌐 Hospedagem e Deployment

### GitHub Pages (Recomendado)

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Ative GitHub Pages nas configurações
4. Seu site estará disponível em: `https://seu-usuario.github.io/cuiaba-digital`

### Outras Opções

- **Netlify** — Drag and drop deployment
- **Vercel** — Otimizado para projetos estáticos
- **Servidor Web Próprio** — Apache, Nginx, etc.

---

## 📝 Notas Importantes

- **Sem Backend:** O formulário de contato é apenas frontend (não envia emails automaticamente)
- **Sem Banco de Dados:** Todas as informações são estáticas
- **Sem Dependências Externas:** Apenas HTML, CSS e JavaScript vanilla
- **Compatibilidade:** Funciona em todos os navegadores modernos

---

## 🚀 Próximos Passos (Sugestões)

1. **Integrar Backend** — Conectar formulário a um servidor
2. **Adicionar Imagens Reais** — Substituir emojis por fotos
3. **Sistema de Reservas** — Integrar com plataformas de booking
4. **Banco de Dados** — Armazenar informações de parceiros
5. **API** — Criar endpoints para dados dinâmicos
6. **PWA** — Transformar em Progressive Web App
7. **Analytics** — Rastrear comportamento dos usuários

---

## 📧 Suporte e Contato

Para dúvidas sobre o projeto, use o formulário de contato no site ou envie um email para:

📧 **contato@cuiabádigital.com.br**

---

## 📄 Licença

Este projeto é fornecido como material educacional. Sinta-se livre para usar, modificar e distribuir conforme necessário.

---

## 🙏 Agradecimentos

Desenvolvido com dedicação para valorizar a cultura, gastronomia e natureza de Cuiabá, Mato Grosso.

**Cuiabá Digital — Conectando Experiências Autênticas** 🌿

---

**Versão:** 1.0  
**Data:** 2024  
**Desenvolvido por:** Manus AI
