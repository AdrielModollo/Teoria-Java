# Encapsulamento

Possuí um padrão e protege o código do usuário e o usuário do código.
Teoria: Ocultar partes independentes da implementação, permitindo construir partes invisíveis ao mundo exterior.

Um bom objeto encapsulado possuí uma Interface: Lista de serviços fornecidos por um componente. É o contato com o mundo exterior, que define o que pode feito com um objeto dessa classe. (Exemplo controle remoto)

Outro exemplo de interface: Image que você está dirigindo seu carro e realiza uma ação de esterçar seu volante, você sabe exatamente o que acontece por dentro de seu veículo para conseguir realizar esta ação? A não ser que você seja um mecanico, engenheiro com certeza você não sabe rsrs. Então o objetivo da interface é justamente este, é dar acesso somente ao exterior(Volante) e o encapsulamento se preocupar com as demais ações, ao qual o usuário final não tem necessidade de acesso. 

Interface não tem atributos, somente metodos. 

Exemplo:
<<Interface>>
  Controlador
  Ligar()
  desligar()
  abrirmenu()
  fecharmenu()
  aumentarVolume()
  diminuirVolume()
  ligarMudo()
  desligarMudo()
  play()
  pause()

  metodos abstratos: Ele é previsto, mas não implementado. Ou seja, só quero saber a reação, exemplo ao clicar no botão ligar a ação será a mesma. 

Encapsular não é obrigatório, mas é uma boa prática para produzir classes mais eficientes.

Vantagens Encapsular:
1°Tornar mudanças invisíveis

2°Facilitar reutilização de código

3°Reduzir efeitos colaterais  


