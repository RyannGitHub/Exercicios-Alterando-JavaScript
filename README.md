# Exercicios-Alterando-JavaScript
Minhas resoluções para alguns exercícios de manipulação de arrays propostos pela Alura.

1. Crie uma função que receba dois arrays e os concatene em um único array.

const instrumentos = ['Guitarra', 'Baixo', 'Bateria', 'Piano'];
const diasDeTrabalho = ['Segunda', 'Quarta', 'Quinta', 'Domingo'];

function concatenarArray(arr1, arr2) {
    const juncaoArrays = arr1.concat(arr2);
    return juncaoArrays   
}

console.log(concatenarArray(instrumentos, diasDeTrabalho));


2. Crie um array chamado numeros contendo números de 1 a 10. Utilize o método slice para criar um novo array chamado parteNumeros que contenha apenas os números de índice 3 a 7 de numeros.


const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

const parteNumeros = numeros.slice(3,8)

console.log(parteNumeros);


3. Dado o array frutas contendo frutas que desejamos comprar na feira:

const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']

Utilize o método splice para remover as frutas no índice 2 e 3 e, em seguida, adicione as frutas 'Kiwi' e 'Pêssego' nesses mesmos índices.


const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']

frutas.splice(2,2, 'Kiwi');

console.log(frutas);

4. Crie dois arrays chamados menuPrincipal e menuDeSobremesas contendo opções do cardápio de um restaurante. Utilize o método concat para criar um novo array menuCompleto contendo todos os elementos de menuPrincipal seguidos pelos elementos de menuDeSobremesas.

const menuPrincipal = ['Carne Bovina', 'Omelete', 'Arroz Branco',];
const menuDeSobremesas = ['Bolo Caramelizado', 'Pudim de Chocolate', 'Sorvete de Pistache'];

const menuCompleto = menuPrincipal.concat(menuDeSobremesas);

console.log(menuCompleto);


