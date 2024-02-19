# Exercicio.1-Trellho
Resoluções dos exercícios do trelho com data de entrega em 19/02

// EXERCIO 1
// Crie uma função que exiba uma mensagem simples no console. Ecolha a mensagem que será exibida no console.log

function exibirMensagem() { 
    console.log(‘Missão dada é missão cumprida!’); 
    
    } 

// EXERCIO 2
// Declare uma variável e atribua um número a ela, em seguida, exiba seu valor no console. Atribua o valor a variável usando o window.prompt();

var numero = window.prompt("Digite um número:");  
  console.log("O número digitado é: " + numero);

// EXERCIO 3
// Combine duas strings usando o operador de concatenação e exiba o resultado no console.

var string1 = "Missão dada, "; 
var string2 = "e missão cumprida!";  

var resultado = `${string1}${string2}`;  
  console.log(resultado);


// EXERCICIO 4
// Crie uma função que receba dois números como parâmetros e retorne sua soma no console.log.

var soma = numero1 + numero2;   
  return soma; 
  }  

var resultadoSoma = somarNumeros(5, 7);  
  console.log("A soma dos números é: " + resultadoSoma);

// EXERCIO 5
// Utilize uma estrutura condicional (if,else) para verificar se um número é positivo, negativo ou zero. Exiba os valores no console.log().

function verificarNumero(numero) {
if (numero > 0) {     
console.log("O número é positivo.");
} else if (numero < 0) {
  console.log("O número é negativo.");   
} else {     
  console.log("O número é zero.");
}

// EXERCIO 6

// Crie 3 objetos com propriedades representando informações pessoais (nome, idade, nacionalidade e profissão) e exiba essas informações com um console.log para cada objeto.

var pessoa1 = {   
  nome: "Sidney",   
  idade: 36,   
  nacionalidade: "Brasileiro",   
  profissao: "Estudante" 
  };  
    console.log("Informações da Pessoa 1:");   
    console.log("Nome: " + pessoa1.nome); 
    console.log("Idade: " + pessoa1.idade); 
    console.log("Nacionalidade: " + pessoa1.nacionalidade);   
    console.log("Profissão: " + pessoa1.profissao); 
    console.log("\n");  
    
var pessoa2 = {  

  nome: "Janaina",   
  idade: 26,   
  nacionalidade: "Brasileira",   
  profissao: "Analista Financeiro" 
  };  
   console.log("Informações da Pessoa 2:"); 
   console.log("Nome: " + pessoa2.nome);   
   console.log("Idade: " + pessoa2.idade); 
   console.log("Nacionalidade: " + pessoa2.nacionalidade);     
   console.log("Profissão: " + pessoa2.profissao); 
   console.log("\n");  
   
var pessoa3 = {  

  nome: "Luzia",     
  idade: 68,   
  nacionalidade: "Brasileiro",   
  profissao: "Aposentada" 
  };  
  console.log("Informações da Pessoa 3:"); 
  console.log("Nome: " + pessoa3.nome);   
  console.log("Idade: " + pessoa3.idade); 
  console.log("Nacionalidade: " + pessoa3.nacionalidade); 
  console.log("Profissão: " + pessoa3.profissao);


// EXERCIO 7
// Função que exibe a saudação com base na hora 

function saudacaoDoDia(hora) {   
  if (hora >= 0 && hora < 12) {     
    console.log("Bom dia!");   
  } else if (hora >= 12 && hora < 18) {     
    console.log("Boa tarde!");   
  } else {     
    console.log("Boa noite!");   
    } 
  }


// EXERCIO 8
// Implemente uma função que determine se um número é par ou ímpar.
- javascript 
- Copy code
function verificarParOuImpar(numero) {
  if (numero % 2 === 0) {
    console.log(numero + " é um número par.");
  } else {
    console.log(numero + " é um número ímpar.");
  }
}


// EXERCICIO 9

// Use um switch para exibir mensagens diferentes com base em uma condição.
// Função que exibe mensagens diferentes com base em uma condição 

function exibirMensagem(condicao) {   
  switch (condicao) {      
    case "manha":       
      console.log("Bom dia!");       
      break;     
    case "tarde":       
      console.log("Boa tarde!");       
      break;     
    case "noite":       
      console.log("Boa noite!");       
      break;     
    default:       
      console.log("Mensagem padrão.");   
  } 
}


// EXERCIO 10
// Crie uma função que solicite para o usuário através do prompt de comando sua idade, e a partir da idade fornecida, exiba uma mensagem informando se ele é maior de idade ou não. Considere 18 anos como maior idade.

function verificarMaioridade() {   
 
  var idade = parseInt(window.prompt("Digite sua idade:")); 
  if (idade >= 18) {     
    console.log("Você é maior de idade!");   
  } else {     
    console.log("Você é menor de idade.");   
  } 
}

// FINALIZADO
