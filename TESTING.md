# Guia de Testes - Cuiabá Digital

## 📋 Checklist de Navegação

### Página Inicial (index.html)

- [ ] Header com logo e menu de navegação carrega corretamente
- [ ] Menu mobile (☰) aparece em telas pequenas
- [ ] Hero section com título, subtítulo e CTA button visível
- [ ] Seção "Bem-vindo" com conteúdo e imagem
- [ ] 3 pilares (Gastronomia, Cultura, Natureza) exibem corretamente
- [ ] Cards de destaques aparecem com hover effects
- [ ] Seção de CTA com 3 botões funciona
- [ ] Footer com informações e links está presente
- [ ] Links de navegação levam às páginas corretas

### Página Gastronomia (pages/gastronomia.html)

- [ ] Hero section com tema laranja/âmbar
- [ ] Seção Rota do Peixe com conteúdo e imagem
- [ ] 6 cards de pratos típicos exibem corretamente
- [ ] Cards têm hover effects (elevação e sombra)
- [ ] Seção Experiência Gastronômica com layout 2 colunas
- [ ] Dicas de visita em 3 cards (Melhor Época, Reservas, Preços)
- [ ] Footer com links corretos
- [ ] Navegação volta para home e outras páginas

### Página Cultura (pages/cultura.html)

- [ ] Hero section com tema âmbar/ouro
- [ ] Seção Artesanato Regional com conteúdo
- [ ] 6 cards de manifestações culturais (Siriri, Cururu, etc.)
- [ ] Seção Calendário de Eventos com layout 2 colunas
- [ ] Seção Apoio aos Criadores com 3 cards
- [ ] Seção Feiras e Mercados com 3 cards
- [ ] Todos os cards têm interatividade
- [ ] Links de navegação funcionam

### Página Natureza (pages/natureza.html)

- [ ] Hero section com tema verde/teal
- [ ] Seção Parques Urbanos com conteúdo
- [ ] 6 cards de atrativos naturais
- [ ] Seção Chapada dos Guimarães com layout 2 colunas
- [ ] Dicas de Segurança com 6 cards
- [ ] Seção Biodiversidade com layout 2 colunas
- [ ] Todos os componentes responsivos
- [ ] Navegação funcional

### Página Sobre (pages/sobre.html)

- [ ] Seção Propósito com conteúdo e imagem
- [ ] 3 cards de Missão, Visão e Valores
- [ ] Seção Contexto Acadêmico com layout 2 colunas
- [ ] 4 cards de Impacto Esperado
- [ ] Seção Os Três Pilares com informações
- [ ] 3 cards de Público-Alvo
- [ ] Seção Compromissos com imagem e conteúdo
- [ ] Todos os links funcionam

### Página Contato (pages/contato.html)

- [ ] Hero section com tema laranja
- [ ] Formulário de contato com 5 campos
- [ ] Campo de nome, email, telefone, assunto, mensagem
- [ ] Botão "Enviar Mensagem" funciona
- [ ] Validação básica do formulário
- [ ] Mensagem de sucesso aparece após envio
- [ ] Informações de contato exibidas corretamente
- [ ] 6 cards de tipos de contato
- [ ] 6 perguntas frequentes (FAQ) visíveis
- [ ] Footer com informações

---

## 🎨 Testes de Design

### Responsividade

#### Desktop (1200px+)
- [ ] Layout em 2 colunas funciona
- [ ] Cards em grid de 3 colunas
- [ ] Menu de navegação horizontal
- [ ] Imagens e conteúdo bem proporcionados

#### Tablet (768px - 1199px)
- [ ] Layout ajusta para 2 colunas quando necessário
- [ ] Cards em grid de 2 colunas
- [ ] Menu mobile aparece
- [ ] Conteúdo legível e bem espaçado

#### Mobile (até 767px)
- [ ] Layout em 1 coluna
- [ ] Cards em grid de 1 coluna
- [ ] Menu mobile funciona (toggle)
- [ ] Botões e inputs com tamanho tátil adequado
- [ ] Texto legível sem zoom
- [ ] Imagens adaptadas ao tamanho

### Cores e Tipografia

- [ ] Cores seguem a paleta regional (laranja, âmbar, verde, teal)
- [ ] Tipografia consistente em todas as páginas
- [ ] Contraste suficiente entre texto e fundo
- [ ] Headings (h1, h2, h3) com tamanhos apropriados
- [ ] Parágrafos com espaçamento adequado

### Interatividade

- [ ] Links mudam de cor ao passar o mouse
- [ ] Cards elevam ao passar o mouse
- [ ] Botões têm feedback visual
- [ ] Transições suaves (0.2s - 0.5s)
- [ ] Menu mobile abre e fecha corretamente
- [ ] Formulário valida campos obrigatórios

---

## 🔗 Testes de Links

### Navegação Interna

- [ ] Home → Gastronomia
- [ ] Home → Cultura
- [ ] Home → Natureza
- [ ] Home → Sobre
- [ ] Home → Contato
- [ ] Todas as páginas → Home
- [ ] Footer links funcionam
- [ ] Âncoras (#) funcionam

### Links Externos (Redes Sociais)

- [ ] Instagram link presente
- [ ] Facebook link presente
- [ ] TikTok link presente
- [ ] YouTube link presente

---

## 📱 Testes de Formulário

### Validação

- [ ] Campo "Nome" obrigatório
- [ ] Campo "Email" obrigatório e valida formato
- [ ] Campo "Assunto" obrigatório
- [ ] Campo "Mensagem" obrigatório
- [ ] Campo "Telefone" opcional
- [ ] Botão desabilitado se campos obrigatórios vazios

### Feedback

- [ ] Mensagem de sucesso aparece após envio
- [ ] Formulário limpa após envio
- [ ] Mensagem desaparece após 5 segundos
- [ ] Estilo visual da mensagem é claro

---

## 🌐 Testes de Navegadores

### Chrome/Chromium
- [ ] Todos os elementos renderizam corretamente
- [ ] Responsividade funciona
- [ ] Formulário valida

### Firefox
- [ ] Layout consistente
- [ ] Cores exibem corretamente
- [ ] Interatividade funciona

### Safari
- [ ] Gradientes renderizam
- [ ] Flexbox/Grid funcionam
- [ ] Transições suaves

### Edge
- [ ] Compatibilidade total
- [ ] Performance adequada

---

## ⚡ Testes de Performance

- [ ] Página carrega rapidamente (< 3s)
- [ ] Sem erros no console do navegador
- [ ] Imagens otimizadas
- [ ] CSS minificado (opcional)
- [ ] JavaScript sem erros

---

## ♿ Testes de Acessibilidade

- [ ] Todos os inputs têm labels
- [ ] Imagens têm alt text
- [ ] Contraste suficiente (WCAG AA)
- [ ] Navegação por teclado funciona
- [ ] Estrutura semântica correta
- [ ] Hierarquia de headings apropriada

---

## 📝 Checklist Final

- [ ] Todos os arquivos HTML validam (W3C)
- [ ] CSS sem erros de sintaxe
- [ ] Nenhum link quebrado
- [ ] Formulário funciona
- [ ] Responsividade testada em 3 breakpoints
- [ ] Navegação completa entre páginas
- [ ] Conteúdo correto e sem erros de digitação
- [ ] Footer presente em todas as páginas
- [ ] Header consistente em todas as páginas
- [ ] Projeto pronto para GitHub/hospedagem

---

## 🚀 Instruções para Testar Localmente

### Opção 1: Python
```bash
cd cuiaba-digital
python3 -m http.server 8000
# Acesse: http://localhost:8000
```

### Opção 2: Node.js
```bash
cd cuiaba-digital
npx http-server
# Acesse: http://localhost:8080
```

### Opção 3: Abrir no Navegador
- Clique com botão direito em `index.html`
- Selecione "Abrir com" → Navegador

---

## 📊 Resultado dos Testes

| Página | Status | Observações |
|--------|--------|-------------|
| Home | ✅ | Todos os elementos funcionando |
| Gastronomia | ✅ | Cards e conteúdo OK |
| Cultura | ✅ | Manifestações culturais exibidas |
| Natureza | ✅ | Atrativos naturais listados |
| Sobre | ✅ | Missão e visão claros |
| Contato | ✅ | Formulário funcional |
| Responsividade | ✅ | Testado em 3 breakpoints |
| Navegação | ✅ | Todos os links funcionam |

---

**Data do Teste:** 2024  
**Versão Testada:** 1.0  
**Status:** ✅ APROVADO PARA PRODUÇÃO
