//desafio 1 alura

//Mostre um alerta com a mensagem "Boas vindas ao nosso site!"
alert("Boas vindas ao nosso site!")

//Declare uma variável chamada nome e atribua a ela o valor "Lua".
let nome  = prompot (lua)

//Crie uma variável chamada idade e atribua a ela o valor 25.
let idade = prompt (25)

//Defina uma variável numeroDeVendas e atribua a ela o valor 50.
let numeroDeVendas = prompt (50)

//Defina uma variável saldoDisponivel e atribua a ela o valor 1000.
let saldoDisponivel = prompt (1000)

//Exiba um alerta com o texto "Erro! Preencha todos os campos"
if (nome == "" || idade == "" || numeroDeVendas == "" || saldoDisponivel == "") {
    alert("Erro! Preencha todos os campos")
}

//Declare uma variável chamada mensagemDeErro e atribua a ela o valor "Erro! Preencha todos os campos" Agora exiba um alerta com o valor da variável mensagemDeErro.
let mensagemDeErro = "Erro! Preencha todos os campos"
alert(mensagemDeErro)

//Use um prompt para perguntar o nome do usuário e armazená-lo na variável nome.
nome = prompt("Qual é o seu nome?")

//Peça ao usuário para digitar sua idade usando um prompt e armazene-a na variável idade.
idade = prompt("Qual é a sua idade?")

//Agora, caso a idade seja maior ou igual que 18, exiba um alerta com a mensagem "Pode tirar a habilitação!".
if (idade < 18) {
    alert ("Você é menor de idade não pode tirar carteira de motorista")
} else {
    alert ("Você é maior de idade pode tirar carteira de motorista")
}
