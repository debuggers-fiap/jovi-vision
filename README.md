# JOVI Vision — Web Development Sprint 2

![JOVI Vision](https://img.shields.io/badge/JOVI-Vision-E91E8C?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-Semântico-orange?style=for-the-badge)
![CSS3](https://img.shields.io/badge/CSS3-Flexbox-blue?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-Puro-yellow?style=for-the-badge)

## Sobre o Projeto

O **JOVI Vision** é uma solução de câmera assistiva para estudantes desenvolvida como protótipo interativo. O sistema transforma a câmera do smartphone JOVI em uma ferramenta educacional com OCR, leitura em voz alta, digitalização de documentos e controle por voz.

---

## Integrantes do Grupo — Debuggers

| Nome Completo | RM |
|---|---|
| Enrico Vieira de Almeida Vidal | RM569217 |
| Vinícius Fuentes Cavalcanti | RM570818 |
| Thiago Fernandes Kulesza | RM568922 |
| Guilherme De Rosa Peres | RM569193 |
| Kelvyn Lukas Junqueira da Silva | RM572950 |

---

## Estrutura do Projeto

```
jovi-vision/
├── login.html      → Tela de login/cadastro com validação
├── index.html      → Protótipo interativo completo com JS
└── README.md       → Este arquivo
```

---

## Funcionalidades JavaScript (Slide 22)

### ✅ Manipulação de Strings e Variáveis
- Formatação automática de nomes (capitalização)
- Geração de nomes de arquivo com timestamp (`JOVI_20260515_001.jpg`)
- Saudação dinâmica por horário (Bom dia / Boa tarde / Boa noite)
- Substituição de palavras para tradução simulada

### ✅ Manipulação de Eventos DOM
- Navegação entre 6 telas via clique nos botões da nav
- Switches de configuração com toggle de estado
- Botões de zoom com destaque ativo
- Flash da câmera com alternância de estilo
- Sliders arrastáveis (mousedown/mousemove/mouseup + touch)
- Shutter com efeito de flash visual

### ✅ Validação de Formulários e Login
- Login com validação de e-mail (regex) e senha (mínimo 6 chars)
- Cadastro com validação de nome, RM (apenas números), e-mail e senha
- Mensagens de erro inline por campo
- Verificação de e-mail duplicado no cadastro

### ✅ Alertas e Prompts
- `alert()` na confirmação de cadastro e logout
- `prompt()` para nome do PDF, exportação e tradução de idioma
- `confirm()` na saída do sistema

### ✅ Manipulação de Imagens (Slideshow)
- Painel lateral com thumbnails dos 4 modos
- Auto-slideshow a cada 5 segundos com highlight ativo
- Clique nos thumbnails navega para o modo correspondente
- Contador de slides `1 / 4`

### ✅ Criação e Gerenciamento de Eventos com DOM
- `addEventListener` em todos os botões interativos
- Eventos de `click`, `mousedown`, `mousemove`, `mouseup`, `touchstart`, `touchmove`, `touchend`, `keydown`
- Criação dinâmica de elementos DOM (thumbnails do slideshow)

### ✅ JavaScript Puro (sem frameworks)
- Zero dependências externas
- Apenas APIs nativas: `Web Speech API`, `navigator.clipboard`, `navigator.share`, `sessionStorage`

---

## Como Usar

1. Abrir `login.html` no navegador
2. Usar credencial de demo: `demo@jovi.com` / `123456`
   _ou cadastrar uma nova conta_
3. Após o login, será redirecionado para `index.html`
4. Navegar entre os modos pelo menu lateral ou pelas pills da câmera

---

## Requisitos Cumpridos (Pontuação)

| Critério | Pontos | Status |
|---|---|---|
| Boas práticas de código | 10 | ✅ |
| Manipulação de strings e variáveis | 20 | ✅ |
| Manipulação de eventos | 30 | ✅ |
| Git e GitHub (organização + 10 commits) | 25 | ✅ |
| Entrega (ZIP + link repositório) | 15 | ✅ |
| **Total** | **100** | |

---

## Disciplina
**Web Development — Sprint 2**
FIAP · Engenharia de Software · Challenge 2026
Parceria: JOVI Smartphone
.

