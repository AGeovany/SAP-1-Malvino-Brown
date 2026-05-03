# SAP-1-Malvino-Brown
Super desafio, mas apresento-lhe minha versão do icônico SAP-1 dos livro Digital Computer Electronics de A. P. Malvino &amp; J. A. Brown (1993). O hardware foi simulado no LogiSim 2.7.1 for Windows. Também disponibilizo alguns códigos (imagem de memória) que devem ser carregados diretamente na RAM (simulada).
Além das instruções originais (LDA, ADD, SUB, OUT e HLT), acrescentei mais duas (JMP e STA, com pequenas alterações no hardware. A palavra de controle passou de 12 para 14 bits. A linha de 8 LEDs do display binário foi substituída por dois displays 7 segmentos. A gravação da RAM é realizada diretamente no circuito, via botão direito do mouse. Após abrir o arquivo GEO_SAP1_v7 no LogiSim, carregue uma imagem de memória, por exemplo SOMA2NUM. Habilite as simulações e aperte o botão verde RESET até que o contador em anel inicie em 100000. 

As novas instruções são JMP e STA. A primeira faz o contador de programa "saltar" para uma posição específica de memória. A segunda, STA copia o conteúdo do Acumulador numa posição específica da memória. Lembrando que a RAM do SAP-1 possui apenas 16 bytes!

JMP possui op-code 1001 ou 9h. Exemplo de aplicação:
JMP f = 9f = saltar para o endereço f da RAM
JMP b = 9b = saltar para o endereço b da RAM

STA possui op-code 1100 ou Ch. Exemplo de aplicação:
STA e = ce = copiar o conteúdo do acumulador na posição e da RAM
STA a = ca = copiar o conteúdo do acumulador na posição a da RAM
