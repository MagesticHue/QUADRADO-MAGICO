/* Programa da OBI de 2011.
       QUADRADO MAGICO. */
#include<stdio.h>
int main(){ 
int m[3][3]; // nesta linha atribui uma matriz de tres dimencoes.
int i,j,s; // aqui atribui os contadores e quem vai receber a soma.

puts("Digite uns Numeros :");
for(i=0;i<3;i++){
	for(j=0;j<3;j++)
	scanf("%i",&m[i][j]);
} // usei dois for, o primeiro para pegar o numero de linha, e o segundo o numero de colunas.
puts("\n"); // use senpre o puts para pular linha, neste codigo nao e obrigatorio, mas e bom se acostumar a colocar puts ou printf para pukar linha na matriz.
  s = m[0][0]+m[0][1] + m[0][2]; // nesta linha faco a soma da primeira linha e atribuo a s para poder comparar no if.
  if(s == m[1][0] + m[1][1 ] + m[1][2] && s== m[2][0] + m[2][1] + m[2][2]) // nesta linha uso o if para saber se as somas de todos os lados sao igual a s. se a soma for igual o quadrado e magico.
  puts("QUADRADO EH MAGICO @_@ *_* $_$");
  else
  puts("QUADRADO NAO EH MAGICO !_! '_' ");
getch();
  return 0;
  
}
