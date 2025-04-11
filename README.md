# revis-o-de-l-gica-de-programa-o
let nome = "Amanda"
let nome1 = 'Amanda'
let numero = 10
let booleano = true

console.log('Conversão de tipos!');

console.log('ano ' + 2024);
console.log('2' + '2');
//conversão explícita
console.log(parseInt('2') + parseInt('2'));

//conversão implícita
console.log('10' / '2');

console.log('6.5');
console.log('6,5');

let cliente = 'Maria'
let maiorDeIdade = true
let saldo = 1000

typeof cliente //string
// o js reconhece string pelo uso de aspas,
simples ou duplas, ou crase

typeof maiorDeIdade //boolean

typeof saldo //number

let nome = "Amanda";
nome = "Maria";
// retorna Maria

const idade = 25;
idade = 30; // Erro:
Atribuição a uma variável
constante

let resultado = 10 +
5; // resultado = 15

let resultado = 10 -
5; // resultado = 5

let resultado = 10 *
5; // resultado = 50

let resultado = 10 /
5; // resultado = 2

E (&&)
Retorna verdadeiro se ambas as
expressões forem verdadeiras.
Ex: (5 > 3) && (10 < 20) // true

OU (||)
Retorna verdadeiro se pelo
menos uma expressão for
verdadeira. Ex: (5 > 3) || (10 <
20) // true

NÃO (!)
Inverte o valor da expressão. Ex:
!(5 > 3) // false

//if, else
let idade = 20;
if (idade >= 18) {
console.log("Você é maior

de idade!");
}
else {

console.log("Você é
menor de idade!");

}

function saudacao() {
console.log("Olá, mundo!");
}
saudacao();

// Função que calcula a soma de dois números e retorna o
resultado
function soma(a, b) {
return a + b;
}

// Chamando a função e armazenando o retorno em uma
variável
let resultado = soma(5, 3);

// Exibindo o resultado no console
console.log("O resultado da soma é:", resultado);

// Função que exibe uma mensagem personalizada
function saudacao(nome, idade) {
console.log(`Olá, ${nome}! Você tem ${idade} anos.`);
}

// Chamando a função com diferentes valores de parâmetros
saudacao("Ana", 25);
saudacao("Carlos", 30);

// Definindo uma função de expressão
const saudacao = function(nome, idade) {
console.log(`Olá, ${nome}! Você tem ${idade} anos.`);
};

// Chamando a função com diferentes valores de parâmetros
saudacao("Ana", 25);
saudacao("Carlos", 30);

const estudante = (notaFinal, faltas) => {
if (notaFinal < 7 && faltas > 4) {
return true
}else {
return false
}
}
