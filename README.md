# Soma-de-5-numero

Exercício 4: Soma 5 números
Gabarito do Exercício 4
Exercício 4: Escreva um algoritmo para ler 5 números inteiros e ao final da leitura escrever a soma total dos 5 números lidos. 

OPÇÃO COM ENQUANTO

programa

{

   funcao inicio(){

      inteiro valor, contagem, soma

      valor = 0

      contagem = 1

      soma = 0

      enquanto(contagem <= 5) {

         leia (valor)

         soma = soma + valor

         contagem = contagem + 1

      }

      escreva("A soma é: ", soma)

   }

}


OPÇÃO COM FAÇA ... ENQUANTO

programa

{

   funcao inicio(){

      inteiro valor, contagem, soma

      valor = 0

      contagem = 1

      soma = 0

      faca {

         leia (valor)

         soma = soma + valor

         contagem = contagem + 1

      } enquanto(contagem <= 5)

      escreva("A soma é: ", soma)

   }

}


OPÇÃO COM PARA

programa

{

   funcao inicio(){

      inteiro valor, soma

      valor = 0

      soma = 0

      para(inteiro contagem = 1; contagem <= 5, contagem++) {

         leia (valor)

         soma = soma + valor

      }

      escreva("A soma é: ", soma)

   }

}
