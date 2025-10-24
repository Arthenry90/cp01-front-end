# Projeto CP2 Front-End - Vinharia Agnello

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
cp02-front-end/
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

Pages: https://arthenry90.github.io/cp02-front-end/

## Efeitos Visuais

Esta seção define os **efeitos de transição, animação e interação visual** aplicados em diferentes elementos da página, com o objetivo de tornar a navegação mais fluida e dinâmica.  
A seguir, estão descritas as **pseudo-classes**, **pseudo-elementos** e **animações** utilizados:

---

### 🔹 Pseudo-elementos

- **`::selection`**  
  Altera o comportamento padrão da seleção de texto: o texto selecionado fica **branco com fundo preto**, criando uma identidade visual própria e consistente com o tema do site.

---
- **`::first-letter`**  
  Adiciona estilização única na primeira letra de determinado texto.

---

### 🔹 Pseudo-classes

- **`:hover`**  
  É ativada quando o usuário passa o cursor do mouse sobre um elemento.  
  Foi aplicada em diversos componentes, como:
  - `#Contato`
  - `.navegacao_principal a`
  - `.caixa_branca`
  - `.produto img`
  - `.descricao`
  - `button.botao`  
  Criando efeitos de destaque, aumento e alteração de cor.

- **`:focus`**  
  É ativada quando um elemento recebe foco, geralmente ao clicar ou digitar em campos de formulário.  
  Foi usada em:
  - `#Contato textarea`
  - `.campoResposta`  
  Para alterar a cor de fundo e sinalizar que o campo está ativo.

- **`:nth-child(odd)`**  
  É utilizada na página principal para mudar a fonte dos elementos pares do menu de navegação principal.
  Foi usada em:
  - `.navegacao_lista li`

---

### 🔹 Animações

- **`.spinning`**  
  Elemento animado com o efeito de rotação contínua.  
  A classe aplica a animação **`spin`**, que gira o elemento de **0° a 360°** de forma **infinita e linear**, com duração de **3 segundos** por ciclo.

- **`@keyframes spin`**  
  Define o movimento de rotação, do estado inicial (`rotate(0deg)`) até o final (`rotate(360deg)`), criando o efeito de **giro contínuo**.

---