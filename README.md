# 🏥 Clínica Médica Life — CM-Life

> Site institucional de uma clínica médica multiespecialidade, desenvolvido com HTML e CSS puro, com layout responsivo e página dedicada a horários de atendimento por especialidade.

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsivo](https://img.shields.io/badge/responsivo-sim-blue)

---

## 📸 Visão Geral

A **Clínica Médica Life** é um site institucional de duas páginas para uma clínica de multiespecialidade. O projeto apresenta a estrutura da clínica, seus diferenciais, especialidades médicas disponíveis com tabelas de horários e profissionais, além de informações de contato e localização via Google Maps.

---

## 🚀 Funcionalidades

- **Header fixo** com logo e navegação entre seções e páginas
- **Hero banner** com imagem de fundo e chamada principal
- **Seção Sobre** com diferenciais da clínica em lista
- **Prévia de Especialidades** na home com cards e link para página completa
- **Página de Especialidades** dedicada com menu de âncoras interno
- **Tabelas de horários** por especialidade com dias, turnos e profissionais responsáveis
- **Seção de Contatos** com informações de agendamento e mapa do Google Maps
- **Rodapé** com logo, telefone e endereço
- **Layout totalmente responsivo** com breakpoints para 425px, 768px e 1024px

---

## 🗂️ Estrutura do Projeto

```
clinica-cm-life/
│
├── pages/
│   ├── index.html            # Página principal (home)
│   └── especialidades.html   # Página de especialidades e horários
│
├── css/
│   ├── home.css              # Estilos globais e da home
│   └── especialidades.css    # Estilos da página de especialidades (importado em conjunto)
│
└── assets/
    ├── logo.png              # Logo da clínica
    ├── recepcao.png          # Imagem do banner principal
    ├── medico.jpg            # Foto da seção sobre
    ├── ortopedia.png         # Imagem da especialidade ortopedia (tabela)
    ├── ortopedia1.png        # Imagem do card de ortopedia (home)
    ├── pediatra.png          # Imagem do card de pediatria (home)
    ├── pediatra2.png         # Imagem da especialidade pediatria (tabela)
    ├── geriatra.png          # Imagem da especialidade geriatria
    ├── psicologo.png         # Imagem da especialidade psicologia
    └── fisioterapia.png      # Imagem da especialidade fisioterapia
```

---

## 🎨 Design & Identidade Visual

Paleta clínica e profissional, com tons de verde-água que transmitem saúde e confiança:

| Cor | Hex | Uso |
|---|---|---|
| Verde-água principal | `#00cad1` | Header, botões, destaque de tabelas |
| Verde-água escuro | `#0d6e71` | Rodapé |
| Verde-água hover | `#004b4c` | Hover em links |
| Cinza suave | `#0000008c` | Textos do corpo |
| Cinza claro | `#f1f1f1` | Linhas da tabela |
| Cinza médio | `#cdcdcd` | Linhas alternadas da tabela |

**Tipografia:** `Source Sans Pro` (Google Fonts) — moderna e de alta legibilidade para contexto médico.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica com `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>` e `<table>`
- **CSS3** — Flexbox, media queries, nth-of-type para tabelas zebradas
- **Google Fonts** — Source Sans Pro
- **Google Maps Embed API** — Localização interativa na seção de contatos

---

## ⚙️ Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/LucasDiasXavier/Clinica-cm-life.git

# Acesse a pasta do projeto
cd clinica-cm-life

# Abra a página inicial no navegador
# Dê duplo clique em pages/index.html ou use o Live Server no VS Code
```

> 💡 **Dica:** Use a extensão **Live Server** do VS Code para evitar problemas com caminhos relativos de assets.

---

## 📱 Responsividade

O projeto conta com três breakpoints bem definidos:

| Breakpoint | Ajustes aplicados |
|---|---|
| `≤ 425px` | Header em coluna, hero reduzido (200px), tabelas sem imagem |
| `≤ 768px` | Hero reduzido (300px), imagem da seção "sobre" oculta, imagens das tabelas ocultas |
| `≤ 1024px` | Hero ajustado para 400px de altura |

---

## 🩺 Especialidades com Horários

A página `especialidades.html` detalha 5 especialidades com tabelas completas de atendimento:

| Especialidade | Profissionais |
|---|---|
| 🦴 Ortopedia | Dra. Daniele Almeida, Dr. Daniel Souza, Dr. Manoel Bento |
| 👶 Pediatria | Dra. Elaine Pinheiro, Dr. Anderson Ramos, Dra. Manoela Foster |
| 👴 Geriatria | Dr. Antônio Freitas, Dr. Alfred Conceição, Dr. Almir Aguiar, Dra. Andrea Almeida |
| 🧠 Psicologia | Dra. Daiane Fagundes, Dr. Daniel Dias, Dra. Beatriz Luz |
| 🤸 Fisioterapia | Dr. Alberto de Paula, Dra. Maria Fernandes, Dra. Elaine Peixoto, Dra. Bianca Rocha |

---

## 📄 Páginas do Projeto

| Página | Descrição |
|---|---|
| `index.html` | Home com hero, sobre, prévia de especialidades, contatos e mapa |
| `especialidades.html` | Página completa com menu interno e tabelas de horários por especialidade |

---

## 👨‍💻 Autor

Desenvolvido por **Lucas Dias Xavier**

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para utilizá-lo como referência ou base para seus próprios projetos.

---

<p align="center">
  🏥 <em>Aqui a gente cuida de você</em>
</p>
