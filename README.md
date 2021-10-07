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

## Microserviços

São serviços independentes, que se comunicam utilizando apis bem definidas. Ou seja, com microserviços conseguimos garantir que quando houver modificações não afete outros serviços diretamente ou todo sistema. Então mesmo que haja uma falha, é possível continuar trabalhando, pois os serviços são isolados.

## SOA

É um estilo de arquitetura independente de tecnologia, que é regido pelos principios de design service orientation (SO).

-Organizar um sistema e separa o mesmo, baseado em serviços.

-Expor aquela funcionalidade que deseja, sem a necessidade que o backend da aplicação seja afetado.

SOA não é uma tecnologia, um produto, web service, projeto de TI, software, metodologia, solução de negócio, middleware, não pode ser comprada, não é um serviço, não é uma ferramenta de produtividade.

### Por que utilizar SOA?

Atender melhor e mais rápido as áreas de negócios. Alinhar a TI com os objetivos do negócio.

Agilidade, habilidade de agira rapidamente as necessidade de mercado. Criando flexíbilidade de processos de negócios.

Reutilizar funcionalidades em processos e organizações empresarias.

Economia de tempo e dinheiro, na entrega de novas funcionalidades. Devido a reutilização de serviços.

