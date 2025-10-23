# Projeto CP1 Front-End - Vinharia Agnello

## Descricao do projeto

Esse projeto faz parte de uma atividade avaliativa, e tem como objetivo o desenvolvimento de um site focado no caso Vinharia Agnello, um comercio familiar que tem como objetivo se modernizar, criando um site.

## Integrantes

- Artur Henrique Siqueira - RM566986
- Davi de Souza Malta - RM560327
- Guilherme de Oliveira Scremin - RM564788
- Gabriel Caramico - RM568409
- Igor Gadote - RM567747

## Estrutura de pastas

```bash
cp01-front-end/
│
├── index.html
├── README.md
├── src/
│   ├── assets/
│   │   ├── imagens/
│   │   └── video/
│   ├── css/
│   │   ├── contato_style.css
│   │   ├── historia_style.css
│   │   ├── produtos_style.css
│   │   ├── sobre_style.css
│   │   └── style.css
│   └── pages/ 
│       ├── contato.html
│       ├── historia.html
│       ├── produtos.html
│       └── sobre.html
```

Na pasta pages estão armazenadas todas as páginas do site, exceto a página inicial, que está localizada no arquivo index.html na raiz do projeto. Já na pasta css estão organizados os estilos específicos para cada uma dessas páginas, garantindo que cada uma tenha sua identidade visual própria. Além disso, existe um arquivo de estilos globais que é aplicado a todo o site.

## Links

Pages: https://arthenry90.github.io/cp01-front-end/

## Efeitos Visuais

Esta seção define os **efeitos de transição, animação e interação visual** aplicados em diferentes elementos da página, com o objetivo de tornar a navegação mais fluida e dinâmica.  
A seguir, estão descritas as **pseudo-classes**, **pseudo-elementos** e **animações** utilizados:

---

### 🔹 Página de Contato

- **`#Contato:hover`**  
  Ao passar o mouse sobre a seção de contato, o elemento aumenta levemente de tamanho (`scale(1.02)`), criando um efeito de destaque.

- **`#Contato textarea:focus`** e **`.campoResposta:focus`**  
  Quando o usuário clica ou digita em um campo de texto, o fundo muda para um tom mais escuro (`#1d1210`), com uma transição suave de **0.5s**, indicando foco ativo.

- **`#Contato button.botao:hover`**  
  O botão muda de cor ao passar o mouse, aplicando a mesma tonalidade escura (`#1d1210`) com uma transição de **0.7s**, transmitindo uma sensação de clique suave.

---

### 🔹 Página Inicial

- **`nav.navegacao_principal`** e **`.navegacao_principal a`**  
  Ambos possuem uma **transição suave de 0.3s** para todas as propriedades, garantindo que qualquer mudança de estado (como hover) ocorra de forma fluida.

- **`.navegacao_principal a:hover`**  
  Os links da navegação se deslocam horizontalmente (`translateX(50px)`) e mudam o fundo para **lightcoral**, gerando um destaque visual que indica interatividade.

- **`.caixa_branca:hover`**  
  Aumenta levemente de tamanho (`scale(1.02)`), criando um efeito de realce em caixas ou seções principais.

---

### 🔹 Pseudo-elementos

- **`::selection`**  
  Altera o comportamento padrão da seleção de texto: o texto selecionado fica **branco com fundo preto**, criando uma identidade visual própria e consistente com o tema do site.

---

### 🔹 Produtos e Imagens

- **`.produto img`**  
  As imagens possuem **transição de 0.4s** e **cursor interativo**.  
  No hover, são ampliadas (`scale(1.1)`), simulando um efeito de zoom e atraindo a atenção do usuário.

- **`.descricao:hover`**  
  Aumenta de tamanho (`scale(1.1)`), destacando descrições ou textos relacionados a produtos.

---

### 🔹 Animações

- **`.spinning`**  
  Elemento animado com o efeito de rotação contínua.  
  A classe aplica a animação **`spin`**, que gira o elemento de **0° a 360°** de forma **infinita e linear**, com duração de **3 segundos** por ciclo.

- **`@keyframes spin`**  
  Define o movimento de rotação, do estado inicial (`rotate(0deg)`) até o final (`rotate(360deg)`), criando o efeito de **giro contínuo**.

---