# :zap: Estude Java - 1º Avaliação de Programação II

> ## __1) Qual a definição de Programação Orietada a Objetos?__
 ### É uma maneira de programar que ajudar a resolver muitos problemas da programação funcional.
----

> ## __2) Qual as vantagens da programação Orientada a Objetos?__
### Ajuda em muito em se organizar e escrever menos, além de concentrar as responsabilidades nos pontos certos, flexibilizando a aplicação, encapsulando a lógica de negócios.
---
> ## __3) Qual o nome dado às variáveis que são declaradas diretamente dentro do escopo da classe?__
### Variável de objeto ou atributo.
---


``` java
1 public static void main(String args[]) {
2   Conta c1;
3   c1 = new Conta();
4 
5   Conta c2;
6   c2 = new Conta();
7 }
```
### No caso acima, é correto dizer que `c1` __faz referência a um objeto__, e ela(`c1`) é uma variável referência.
---
# Modificadores de Acesso e Atributos de Classe

> ## __4) Quais são o modificadores de acesso em java?__
- `- private` - É o modificador de acesso mais restritivo que existe. Atributos e métodos declarados como __private__ são acessíveis somente pela classe que os declara.
- `+ public` - Atributos, métodos e classes declarados como __public__ são acessíveis por qualquer classe do Java.
- `# protected` - Atributos e métodos declarados como __protected__ são acessíveis pela classe que os declara, suas subclasses em outros pacotes e outras classes dentro do mesmo pacote.
---
> ## __5) O que é encapsulamento?__
 ### Encapsulamento é o processo de esconder todos os detalhes de um objeto que não contribuem para as suas características essenciais. Ou seja, encapsular é esconder os detalhes de implementação do seu código.
 ---
> ## __6) O que é polimorfismo?__
### Encapsular é separar o programa em partes, deixando ele o mais separado possível. Isso com o intuito de proteger os dados manipulados dentro da classe.
---
> ## __7)Em encapsulamento, os métodos setteres e getteres servem para quê?__
- `Setters` - serve para definir, geralmente, é um método público que não retorna nada , isto é, do tipo **`void`**.
- `Getters` - serve para obter algum valor que foi definidor previamente, geralmente, com o método set do mesmo atributo; geralmente, retorna o dado do mesmo tipo do atribuo..

**Exemplo:**
```java
//Nota: Arquivo Conta.java
class Conta {
    //Criação dos atributos:
    private double saldo;

    // Obtém o valor do atributo 'saldo'
    public double getSaldo() {
        return this.saldo;
    }

    // Define o valor do atributo 'saldo'
    public void setSaldo(double saldo) {
        this.saldo=saldo;
    }

}
//Nota: Arquivo Teste.java
class Teste{

    public static void main(String[] args){

        Conta conta = new Conta();

        conta.setSaldo(2000);

        System.out.printl("Valor  do Saldo: "+conta.getSaldo());
        //Saída: Valor do Saldo: 2000
    }

}
```









---

 __REFERÊNCIAS:__

 1. Encapsulamento - https://webserver2.tecgraf.puc-rio.br/~marcio/cursos/oo/encapsul.htm
 2. Encapsulamento e métodos Get e Set - https://pt.stackoverflow.com/questions/120249/encapsulamento-e-m%c3%a9todos-get-e-set
3. Qual a relação entre encapsulamento e polimorfismo? - 
 https://pt.stackoverflow.com/questions/214767/qual-a-rela%c3%a7%c3%a3o-entre-encapsulamento-e-polimorfismo

4. Getters e setters são uma ilusão do encapsulamento? - https://pt.stackoverflow.com/questions/25995/getters-e-setters-s%c3%a3o-uma-ilus%c3%a3o-do-encapsulamento