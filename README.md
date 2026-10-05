# 🏹 Ficha de Herói — Lyra Vento-Negro

Projeto prático de **HTML e CSS** que simula a tela de status de um personagem original de RPG, com identidade visual autoral e estrutura semântica. Esta é a **Parte 1** do projeto — a base que receberá interatividade com JavaScript na Parte 2.

---

## 📖 Sobre o projeto

Diferente de um portfólio pessoal tradicional, este projeto propõe algo mais lúdico e autoral: uma **ficha de herói de RPG** em formato de página web, como se fosse a tela de status de um jogo. O objetivo é praticar HTML semântico e CSS moderno enquanto se aplica fundamentos de **UI/UX** (hierarquia visual, contraste, proximidade, consistência e acessibilidade).

### 🎯 Objetivos de aprendizagem

- Estruturação semântica com HTML5 (`<header>`, `<section>`, `<article>`, `<main>`)
- Estilização moderna com CSS3 (variáveis, Grid, Flexbox, gradientes, media queries)
- Aplicação de princípios de UI/UX em um layout temático
- Preparação da estrutura para interatividade futura com JavaScript

### 🧩 Funcionalidades da Parte 1

- Cabeçalho com retrato, nome, classe, raça, nível e alinhamento
- Barras de status (HP, MP e XP) com preenchimento visual proporcional
- Grade de atributos primários (Força, Destreza, Constituição, Inteligência, Sabedoria e Carisma)
- Bloco de habilidades especiais com efeitos e custo de MP
- Inventário com itens equipados e consumíveis
- Seção de história expandida do personagem
- Layout responsivo para telas pequenas

---

## 👤 O personagem

**Lyra Vento-Negro** é uma **meio-elfa Arqueira das Sombras** de nível 12, de alinhamento **Caótica Boa**.

Nascida numa noite de eclipse na aldeia élfica de **Vael'Nara**, Lyra viu sua vila ser destruída por um culto devoto à deusa esquecida **Nyxara, a Senhora das Sombras**. Adotada pelo caçador **Thalon Vento-Negro**, foi treinada pela **Ordem dos Caçadores Noturnos** — uma sociedade secreta que caça criaturas que se alimentam do medo.

Hoje carrega o arco élfico de sua mãe, um fragmento amaldiçoado do **Coração de Umbra** e a pergunta que ainda não ousa responder:

> *"Quando a vingança termina... quem eu me torno?"*

### 📊 Atributos

| Atributo | Valor |
|---|---|
| Força | 12 |
| Destreza | 20 |
| Constituição | 14 |
| Inteligência | 16 |
| Sabedoria | 18 |
| Carisma | 11 |

### ⚔️ Habilidades

| Habilidade | Efeito | Custo |
|---|---|---|
| **Flecha Sombria** | 3d8 de dano perfurante + cegueira por 2 turnos | 25 MP |
| **Passo das Sombras** | Teleporte até 9 m para uma área na penumbra | 15 MP |
| **Marca do Caçador** | +2d6 de dano contra um alvo por 3 turnos | 20 MP |

---

## 🎨 Sobre o design (UI/UX)

O layout aplica princípios fundamentais de UI/UX:

- **Hierarquia visual** — nome e nível em destaque; atributos e itens em blocos secundários
- **Contraste** — fundo escuro com acentos dourados, remetendo à fantasia sombria
- **Proximidade** — informações relacionadas agrupadas em "cards"
- **Consistência** — mesma paleta, tipografia e espaçamento em todos os blocos
- **Acessibilidade** — HTML semântico, atributos `alt` e contraste adequado
- **Responsividade** — layout adaptado para telas pequenas via media query

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **CSS3** — variáveis, Grid, Flexbox, gradientes e media queries
- *(Em breve)* **JavaScript** — interatividade da Parte 2
