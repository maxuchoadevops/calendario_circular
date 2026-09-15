# 📅 Circular Calendar

Um projeto web interativo que exibe a data e hora atuais em uma interface circular estilizada, utilizando CSS transformações e animações.

## 🚀 Sobre o Projeto

O **Circular Calendar** é uma visualização de relógio e calendário em formato radial. O design utiliza múltiplos "dials" (mostradores) concêntricos para representar o dia da semana, o mês e o dia do mês, com um relógio central animado.

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estrutura semântica para os mostradores e relógio.
* **CSS3**: Responsável por toda a complexa geometria radial, posicionamento absoluto, transformações (`rotate`, `transform-origin`) e transições suaves.
* **Fontes**: Integração com *Roboto Mono* para um visual moderno e técnico.
* **Font Awesome**: Utilizado para ícones (se aplicável na implementação completa).

## 💡 Principais Funcionalidades

* **Interface Radial**: Layout circular baseado em cálculos precisos de rotação.
* **Design Minimalista**: Fundo escuro (`#292929`) com alto contraste para os elementos.
* **Transições Fluídas**: Uso de propriedades de transição CSS para alterações de estado visual.

## ⚙️ Como visualizar

Como o projeto é composto por arquivos estáticos:

1. Clone este repositório ou baixe o arquivo contendo o código.
2. Certifique-se de que o arquivo HTML esteja na pasta raiz.
3. Abra o arquivo `index.html` em qualquer navegador moderno.

## 📝 Observações Técnicas

O projeto utiliza um sistema de posicionamento radial onde cada elemento (caractere ou mostrador) possui um grau de rotação calculado especificamente para formar o círculo. 

* **Estilização**: As classes `.char1`, `.char2`, etc., são usadas para posicionar cada letra/número individualmente ao redor do centro.
* **Responsividade**: As posições dos elementos são definidas através de cálculos de `transform: rotate()` no CSS, criando o efeito visual de texto em arco.

## Imagem do Projeto:
Acesse: https://i-love-you-mymk.vercel.app/

<img src="img/imagem do projeto.png" alt="imagem do projeto">

---
*Este projeto foi desenvolvido como um experimento de design de interfaces e manipulação de elementos via CSS.*
