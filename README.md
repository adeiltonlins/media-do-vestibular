# media-do-vestibular
Algoritmo "media de alunos"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   :adeilton
// Descrição   : calcular media e retorna valores
// Autor(a)    : adeilton
// Data atual  : 22/07/2022
Var

    notas : vetor[1..100] de real
    media, maior , menor  : real
    i: inteiro


Inicio


para i de 1 ate 25 faca

       escreval("Cadastre o aluno da turma A", i, "º nota:")
          leia(notas[i])

   fimpara

para i de 25 ate 50 faca

       escreval("Cadastre o aluno da turma B", i, "º nota:")
          leia(notas[i])
    fimpara
    
para i de 50 ate 75 faca

       escreval("Cadastre o aluno da turma C", i, "º nota:")
          leia(notas[i])

      fimpara
         
para i de 75 ate 100 faca

       escreval("Cadastre o aluno da turma D", i, "º nota:")
          leia(notas[i])

          


fimpara

 maior:= notas [1]
 menor:= notas [7]


         para i de 2 até 100 faca:
         

     se notas [i]> maior entao
     menor:= notas [i]
 fimse

  se notas [i]< menor então
  menor:= notas[i]

  fimse
fimpara

           media:= (notas [1] + notas [2] + notas [3] + notas [4] + notas [5])
           
           escreval(" ")
           escreval(" a media da trma e:", media)
           escreval(" a maior nota da turma e:" , maior)
           escreval("a menor nota da turma é:", menor)

           
Fimalgoritmo
