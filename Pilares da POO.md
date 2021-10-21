# Encapsulamento

Possuí um padrão e protege o código do usuário e o usuário do código.
Teoria: Ocultar partes independentes da implementação, permitindo construir partes invisíveis ao mundo exterior.

Um bom objeto encapsulado possuí uma Interface: Lista de serviços fornecidos por um componente. É o contato com o mundo exterior, que define o que pode feito com um objeto dessa classe. (Exemplo controle remoto)

Outro exemplo de interface: Imagine que você está dirigindo seu carro e realiza uma ação de esterçar seu volante, você sabe exatamente o que acontece por dentro de seu veículo para conseguir realizar esta ação? A não ser que você seja um mecanico, engenheiro com certeza você não sabe rsrs. Então o objetivo da interface é justamente este, é dar acesso somente ao exterior(Volante) e o encapsulamento se preocupar com as demais ações, ao qual o usuário final não tem necessidade de acesso. 

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
  
 Classe:
  ControleRemoto
    Volume
    Ligando
    Tocando
  

Encapsular não é obrigatório, mas é uma boa prática para produzir classes mais eficientes.

Vantagens Encapsular:
1°Tornar mudanças invisíveis

2°Facilitar reutilização de código

3°Reduzir efeitos colaterais  
  
  
Codando:
  
Interface Controlador
   public abstrato Metodo ligar()
   public abstrato Metodo desligar()
   public abstrato Metodo abrirMenu()
   public abstrato Metodo fecharMenu()
   public abstrato Metodo aumentarVolume()
   public abstrato Metodo diminuirVolume()
   public abstrato Metodo ligarMudo()
   public abstrato Metodo desligarMudo()
   public abstrato Metodo play()
   public abstrato Metodo pause()
FimInterface
  
Clase ControleRemoto
  //Atributos
  private int volume
  private boolean ligado
  private boolean tocando
  //Metodos Especiais
  public Metodo Construtor()
    volume = 50
    ligando = falso
    tocando falso
  FimMetodo
  private Metodo getVolume()
    return volume
  FimMetodo
  private Metodo getLigado()
    return volume
  FimMetodo
  private Metodo getTocando()
    return volume
  FimMetodo
  private Metodo setVolume(v : int)
    volume = v
  FimMetodo
  private Metodo setLigado(1: boolean)
    ligado = 1 
  FimMetodo
  private Metodo setTocando(t: boolean)
    tocando = t
  FimMetodo
FimClasse

