# Neon Digital Clock Component

Um componente de relógio digital (Digital Clock) moderno, minimalista e de alta performance desenvolvido com HTML5, CSS3 e JavaScript. O projeto apresenta um marcador de tempo em tempo real com formato de 12 horas (AM/PM), destacando uma tipografia digital futurista com brilho neon cian sobre um fundo escuro imersivo.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do contêiner do relógio e dos blocos de exibição das horas, minutos, segundos e período.
* CSS3: Estilização completa, uso de fontes digitais customizadas, efeitos de sombra de texto (*text-shadow*) e gerenciamento de contraste para o modo escuro.
* JavaScript: Manipulação do objeto nativo `Date`, lógica de formatação de strings (adição de zeros à esquerda) e atualização contínua do DOM em tempo real.

## Funcionalidades e Técnicas Aplicadas

* Atualização em Tempo Real de Alta Performance: Uso do método `setInterval` configurado para sincronizar e renderizar a hora exata do sistema a cada segundo (1000ms) de forma leve e otimizada.
* Estética Neon Glow Futurista: Aplicação estratégica da propriedade `text-shadow` e `box-shadow` em tons de cian/azul-turquesa brilhante, simulando o efeito luminoso de painéis de LED ou interfaces de ficção científica (Sci-Fi).
* Formatação Completa de 12 Horas: Lógica condicional implementada para converter o formato militar (24h) e anexar dinamicamente os indicadores textuais "AM" ou "PM" ao final da string de tempo.
* Design Clean em Modo Escuro (Dark Mode): O display do relógio é encapsulado em uma caixa retangular preta com cantos suavizados e uma sombra sutil projetada, centralizado perfeitamente sobre um plano de fundo escuro fosco para eliminar distrações.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone
