# 📱 Wide Coverage Location - Mobile First

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

> Uma landing page otimizada e 100% responsiva para dispositivos móveis, desenvolvida através da adaptação de um layout desktop original.

## 📌 Sobre o Projeto

Este projeto é um desafio de CSS focado em **responsividade**. O objetivo principal foi pegar uma estrutura HTML existente — com estilos iniciais engessados em medidas absolutas para desktop — e criar um arquivo `mobile.css` capaz de reorganizar todo o layout para smartphones e tablets, seguindo fielmente um design de referência (mockup).

O maior desafio técnico resolvido neste projeto foi **inverter a ordem visual dos elementos** (colocando o texto acima da ilustração no mobile) utilizando apenas CSS, sem modificar a marcação original do HTML.


## 🛠️ Funcionalidades e Soluções Aplicadas

- **Layout Fluido:** Substituição de larguras e margens fixas (pixels) por porcentagens (`100%`) e `max-width`, eliminando barras de rolagem horizontais em telas pequenas.
- **Flexbox Avançado:** Utilização da propriedade `order` para reestruturar a hierarquia visual do container principal (`main`), garantindo que o texto apareça antes da imagem no mobile.
- **Media Queries:** Implementação de um *breakpoint* (`@media (max-width: 768px)`) para isolar o comportamento mobile sem afetar a versão desktop.
- **Otimização de Navegação:** Ocultação de links de navegação secundários para focar a conversão no botão principal (*Call to Action*).

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estruturação semântica.
- **CSS3:** Estilização, Flexbox, Media Queries e reordenação de fluxo visual.

Desenvolvido por **Ronaldo Melo** 🚀
