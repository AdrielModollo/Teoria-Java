# Teoria-Java

## Maven

Maven é uma ferramenta de interação de projetos. É responsável por gerenciar dependências, controlar versão de artefatos, gerar relatórios de produtividade, garantir a execução de testes, manter nível de qualidade de código dentre outras.

## Spring Boot

É um framework que agiliza o processo de criação de arquivos, assim permitindo ganhar tempo em configurações iniciais e te fornecendo varios recursos já prontos para ser utilizados. 

## O que é uma classe?

Uma classe é utilizar para representar um objeto do mundo real, onde geralmente é declarado atributos e metodos que compoe as caracteristicas e comportamento deste objeto.

## O que são atributos?

Atributos são propriedades de um objeto, ou como mais conhecida em outra linguagens (variável), ou seja é responsável pela declaração destes dados, assim permitindo futramente atribuirmos ações através de nossos metódos.

## O que são metódos?

Metódos é responsável por todo comportamento, ou seja ação que será realizada. Pode-se utilzar mais de um metódos para concluír varias ações, em outras linguagens poderiamos comparar que um metódos nada mais é que uma subrotina, função...

### Estrutura O.O

  Classe
  
  public class CachorroPequeno {
      
        public String nome;
        public float altura;
        public float peso;
        
        void imc {
          if (altura <= 30 && peso <= 5) {
            System.out.println("Parabéns seu cachorro está dentro do peso");
          } else {
            System.out.println("Seu cachorro está obesooo, cuidadooo, cuida do seu doguinho!")
          }
         }
      }
  
 #### Note que a classe "CachorroPequeno" foi declarada no intuito de atribuirmos um objeto do mundo real, em seguida declaramos seus atributos que todo cachorro possuí, ou seja, um nome, uma altura, um peso, claro que poderiamos declarar muito mais, mas para afins de exemplo preferi declarar somente estes para ser de fácil compreendimento. Para finalizar declarei um metódo com nome "imc", este metódo é responsável por toda ação, onde será definido se este cachorro está dentro do peso ou não conforme as condições atribuidas. 
