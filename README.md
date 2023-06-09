# empresaJava
Problema de cadastro de funcionários de determinada empresa solucionado em Java.

## Sobre o problema em questão. ##

Uma empresa deseja controlar os dados de todos os seus funcionários, divididos em duas
categorias: funcionários administrativos e funcionários de vendas. Para isso, foram levantadas
algumas informações sobre as características de cada tipo de funcionário.

● Um funcionário administrativo tem como características: nome, e-mail, salário base, cargo
e departamento.
● Um funcionário de vendas tem como características: nome, e-mail, salário base, cargo e
valor total em vendas realizadas.


Escreva as classes necessárias para representar o enunciado usando o conceito de herança e
as boas práticas de encapsulamento.

Escreva os atributos e métodos das classes de acordo com os seguintes requisitos:
● Todos os funcionários podem consultar o seu salário total através de um método
específico para isso, onde é calculado o salário base acrescido de 5% do valor total em
vendas realizadas, no caso dos funcionários de vendas.

● Todo funcionário, ao ser criado, deve ter obrigatoriamente o nome, e-mail, salário base
e cargo.

● Os funcionários de vendas devem ter um método para registrar uma venda, que atualiza
o seu valor total em vendas realizadas.

● As classes devem ter os métodos getters e setters necessários.

Crie uma classe Empresa com a função main que instancie pelo menos um objeto de cada tipo
de funcionário criado e demonstre o uso dos métodos implementados. Não é preciso ler os
dados do usuário, basta declarar no código.
