exercicios 
Escreva um programa que verifique se um número é positivo, negativo ou zero.
resposta
var num = 5;

if (num > 0) {
  console.log("O número é positivo");
} else if (num < 0) {
  console.log("O número é negativo");
} else {
  console.log("O número é zero");
}
Escreva um programa que verifique se um número é par ou ímpar.
resposta
var num = 4;

if (num % 2 === 0) {
  console.log("O número é par");
} else {
  console.log("O número é ímpar");
}
Escreva um programa que verifique se uma pessoa tem idade suficiente para votar (18 anos ou mais).
resposta
var idade = 20;

if (idade >= 18) {
  console.log("Você tem idade suficiente para votar");
} else {
  console.log("Você ainda não tem idade suficiente para votar");
}
Escreva um programa que verifique se uma pessoa pode dirigir (idade maior ou igual a 18 anos e habilitação válida).
resposta
var idade = 20;
var cnh = true;

if (idade >= 18 && cnh) {
  console.log("Você pode dirigir");
} else {
  console.log("Você não pode dirigir");
}
Escreva um programa que verifique se um número é divisível por 3 e 5.
resposta
var num = 15;

if (num % 3 === 0 && num % 5 === 0) {
  console.log("O número é divisível por 3 e 5");
} else {
  console.log("O número não é divisível por 3 e 5");
}
Escreva um programa que verifique se uma pessoa pode se propor (idade maior ou igual a 65 anos ou tempo de contribuição maior ou igual a 30 anos).
resposta
var idade = 70;
var contricuicao = 35;

if (idade >= 65 || contribuicao >= 30) {
  console.log("Você pode se aposentar");
} else {
  console.log("Você ainda não pode se aposentar");
}
Escreva um programa que verifique se uma pessoa pode obter um empréstimo (renda mensal maior ou igual a 1000 e não possui nenhuma dívida em aberto).
resposta
var renda = 1200;
var debito = false;

if (renda >= 1000 && !debito) {
  console.log("Você pode obter um empréstimo");
} else {
  console.log("Você não pode obter um empréstimo");
}
Escreva um programa que verifique se uma pessoa é adolescente (idade entre 13 e 19 anos).
resposta
var idade = 15;

if (idade >= 13 && idade <= 19) {
  console.log("Você é um adolescente");
} else {
  console.log("Você não é um adolescente");
}
Escreva um programa que verifique se um ano é bissexto (divisível por 4 e não divisível por 100 ou divisível por 400).
Clique para visualizar a resposta
Escreva um programa que verifique se uma pessoa pode entrar em uma montanha-russa (altura maior ou igual a 1,5 metros e idade maior ou igual a 12 anos).
resposta
var altura = 1.6;
var idade = 15;

if (altura >= 1.5 && idade >= 12) {
  console.log("Você pode entrar na montanha-russa");
} else {
  console.log("Você não pode entrar na montanha-russa");
}
DESAFIO Escreva um programa que verifique se um número é um quadrado perfeito.
resposta
var num = 25;
var sqrt = Math.sqrt(num);

if (sqrt % 1 === 0) {
  console.log("O número é um quadrado perfeito");
} else {
  console.log("O número não é um quadrado perfeito");
}
Escreva um programa que verifica se uma pessoa tem acesso à área VIP (nome na lista e idade maior ou igual a 21 anos).
resposta
var nome = "João";
var idade = 25;
var estaNaLista = true;

if (idade >= 21 && estaNaLista) {
  console.log("Você tem acesso à área VIP");
} else {
  console.log("Você não tem acesso à área VIP");
}
Escreva um programa que verifique se um número é par e maior que 10.
resposta
var num = 12;

if (num % 2 === 0 && num > 10) {
  console.log("O número é par e maior que 10");
} else {
  console.log("O número não é par e maior que 10");
}
