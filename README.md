# Estude Java - 1º Avaliação de Programação II

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
- `- private` - É o modificador de acesso mais restritivo que existe. Atributos e métodos declarados como __private__ são acessíveis somente pela classe que os declara
- `+ public` - Atributos, métodos e classes declarados como __public__ são acessíveis por qualquer classe do Java.
- `# protected` - Atributos e métodos declarados como __protected__ são acessíveis pela classe que os declara, suas subclasses em outros pacotes e outras classes dentro do mesmo pacote

