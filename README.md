# Jogo da Vida de Conway — Demo interativa

Simulação de autômatos celulares feita para o seminário de **Teoria da Computação** (AV2) da **UFC – Campus Russas**, com o tema *Computação Biológica e Autômatos Celulares*.

🔗 **Acesse:** https://alanasena.github.io/jogo-da-vida-conway/

## O que tem

### Jogo da Vida (2D)
- Grade editável: clique e arraste para desenhar células
- Play, pausa, passo a passo e controle de velocidade
- Contador de geração e de células vivas
- Bordas conectadas (toro) opcionais
- Padrões prontos: Bloco, Blinker, Pulsar, Glider, Nave (LWSS), Glider Gun de Gosper, R-pentominó e Acorn

### Autômato 1D (Wolfram)
- Regras 110, 30 e 90, ou qualquer regra de 0 a 255
- Tabela de transição com as 8 combinações de vizinhança
- Início com uma célula ou com linha aleatória

## A regra B3/S23

| Situação | Vizinhas vivas | Próxima geração |
| --- | --- | --- |
| Morta | exatamente 3 | Nasce |
| Viva | 2 ou 3 | Sobrevive |
| Viva | qualquer outro número | Morre |

## Como rodar

É um único arquivo HTML, sem dependências. Basta abrir o `index.html` no navegador.

## Tecnologias

HTML, CSS e JavaScript puro, com Canvas API.

## Equipe

- Alana Oliveira de Sena
- Gabriela Sousa de Oliveira
- Robson Camilo Silva Franklin

Professor: Cenez Araújo de Rezende
