# Trabalho 1

Guilherme Yukiyasu Hori Piorno
2 de junho de 2024

## Entrega
  O trabalho foi realizado em cima do exemplo do enunciado, o arquivo onde todos os itens são apresentados é `trabalho.html`.
  
Os itens podem ser localizados buscando pelos comentários referentes a cada item:
1. Trabalho-Item-1
2. Trabalho-Item-2
3. Trabalho-Item-3
4. Trabalho-Item-4
5. Trabalho-Item-5
6. Trabalho-Item-6

Arquivos que foram alterados foram:
```
exampleWebGLApp.html -> renomeado para trabalho.html
shapes2d.js
shapes2dWebGL.js
```


Todos os itens estão apresentados simultaneamente no mesmo canvas e enumerados na imagem abaixo.
![Canvas.](/Imagem.png)

1. Retângulo como pedido.
2. Linha como pedido.
3. Elipse como pedido.
4. Retângulo deslocado de posição, triângulo em escala de 10%, Elipse rotacionada em sentido anti-horário, e outro retângulo deformado por cisalhamento.
5. Polígono preenchido com método de corte de orelhas. Utiliza o algorítmo sugerido de O(n³) para "recorte" de triângulos e os armazena no modelo já criado de lista de triângulos. O algorítmo recursivo utilizado é uma implementação do recomendado pelo artigo enviado junto ao enunciado e a implementação da checagem de área interna do triângulo é a implementação direta do código também enviado. O modelo final retornado no caso de poligono preenchido nada mais é do que o modelo da lista de triângulos que compõe o polígono.
6. Foi utilizado Date().getTime() para calcular o tempo decorrido e assim passar uma varíavel que dependia do tempo. A função seno foi então utilizada para fazer com que o triângulo inferior oscile da esquerda a direita. A mudança no shader foi feita através de uma variável uniforme que altera o valor da componente x do vetor 4D "pos".
