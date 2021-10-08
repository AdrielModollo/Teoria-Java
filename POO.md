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

Estou instanciando uma classe em objeto:
C1 = nova Caneta

C1.cor = "Azul"

C1.ponta = 0.5

C1.tampada = falso

C1.rabiscar() <- Parenteses indica um metódo. 

# Classe

Define os atributos e métodos comuns que serão compartilhados por um objeto.

# Objeto

É uma instância de um classe

# Modificadores de visibilidade

publico(+) A classe atual e todas as classes. Exemplo: Um orelhão (Telefone publico)

privado(-) Somente a classe atual vai ter acesso. Exemplo: Meu celular (Somente eu tenho acesso)

protegido(#) a classe atual e todas suas sub-classe (Só minha mãe e os filhos dela pode utilizar, um telefone em casa)
