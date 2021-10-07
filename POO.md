# Programação Orientada a Objeto

# História

Programação baixo nivel > Programação linear > Programação estruturada > Programação Modular > POO

Quem criou?
Alan Kay

Vantagens POO:

COMERNada

Confiável: O Isolamente entre as parte gera software seguro. Ao alterar uma parte, nenhuma outra é afetada.

Oportuno: Ao dividir tudo em partes, várias delas podem ser desenvolvidas parelelo.

Manutenível: Atualizar um software é mais fácil. Uma pequena modificação vai beneficiar todas as partes que usarem
o objeto. 

Extensível: O Software não é estático. Ele deve crescer para permanecer útil.

Reutilizável: Podemos usar objetos de um sistema que criamos em outro sistema no futuro.

Natural: Mais fácil de entender. Você se precoupa mais na funcionalidade do que nos detalhes de implementação.

# O que é um objeto

Coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio das suas caracteristicas, comportamentos e estado atual.

Exemplo: Uma caneta em sí é um objeto, porém o molde de uma caneta já é uma classe.

Todo objeto tem:
Coisas que eu tenho? Modelo, cor, ponta, carga, tampada (Atributos)
Coisa que eu faço? Escrever, Rabiscar, Pintar, tampar, destampar (Classe)
Como eu estou agora? A Caneta é azul, no momento ela está está estável (Estado)

Classe Caneta
  modelo: Caractere
  cor: Caractere
  ponta: Real
  carga: Inteiro
  tampada: Logico
  
  Metodo rabiscar()
    Se (tampada) entao
      Escreva ("Erro")
    Senao
      Escreva("Rabisco")
    FimSe
  FimMetodo
  
  Metodo tampar()
    tampada = verdadeiro
  FimMetodo
FimClasse
