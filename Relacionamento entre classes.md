classe Lutador

  privado nome: Caractere
  
  privado nacionalidade: Caractere
  
  privado idade: inteiro
  
  privado altura: real
  
  privado peso: real
  
  privado categoria: Caractere
  
  privado vitorias: inteiro
  
  privado derrotas: inteiro
  
  privado empate: Inteiro
  
  //Métodos
  
  publico metodo apresentar()
  
  fim metodo
  
  publico metodo Status()
  
  fim metodo
  
  public metodo ganharLuta()
  
  fim metodo
  
  public metodo perderLuta()
  
  fim metodo
  
  publico metodo empatarLuta()
  
  fim metodo
  
 FimClasse
 
 # Metodo construtor
 
 publico metodo construtor( nome = no: Caractere, nacionalidade = na: Caractere, idade = id: Inteiro, altura = al: Real, setPeso(pe): Real, vitorias = vi: Inteiro, derrotas  = de: Inteiro, empates = em: Inteiro)
 
 fim metodo
 FimClasse
 
 # getters and setters
 
 privado nome: Caractere
 
 privado peso: real
 
 privado categoria: caractere
 
 
 public metodo getNome()
 
  retorne nome
  
 fim metodo
 
 public metodo setNome(no:Caractere)
 
  nome = no
  
 fim metodo
 
 public metodo getPeso()
 
  retorno peso
  
 fim metodo
 
 public metodo setPeso(pe: Caractere) 
 
  peso = pe
  
  setCategoria()
  
 fim metodo
 
 public metodo setCategoria()
 
  set(peso<52.2) entao
  
    categoria = "Inválido"
    
  senao se(peso<=70.3)entao
  
    categoria = "Leve"
    
  senao se(peso <= 83.9) entao
  
    categoria = "Médio"
    
  senao se (peso<=120.2) entao
  
    categoria = "Pesado"
    
  senao 
  
    categoria = "Invalido"
    
   fim se
   
  fim metodo
  
FimClasse
 
  
