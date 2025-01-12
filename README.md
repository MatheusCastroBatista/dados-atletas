Projeto de Cálculo de Parâmetros de Atletas

Olá, meu nome é Matheus Castro, e este repositório faz parte de um curso de lógica de programação do DEVstart. O projeto aqui desenvolvido trata-se de um software capaz de receber informações de atletas e calcular parâmetros importantes, como categoria, IMC e média válida das notas, com base em regras específicas.

Sobre o Projeto

Este projeto é um exemplo prático para aprender lógica de programação utilizando JavaScript. Ele foi desenvolvido para praticar conceitos fundamentais, como classes, métodos e manipulação de arrays.

Estrutura do Projeto

Arquivo Principal

O código principal está contido em um arquivo JavaScript que realiza os seguintes processos:

Classe Atleta

Representa um atleta com os seguintes atributos:

nome: Nome do atleta.

idade: Idade do atleta.

peso: Peso do atleta.

altura: Altura do atleta.

notas: Array contendo as notas recebidas pelo atleta.

Métodos da Classe Atleta

calculaCategoria():

Calcula a categoria do atleta com base na sua idade:

Infantil: 9 a 11 anos.

Juvenil: 12 a 13 anos.

Intermediário: 14 a 15 anos.

Adulto: 16 a 30 anos.

Sem categoria: demais idades.

calculaIMC():

Calcula o Índice de Massa Corporal (IMC) usando a fórmula: IMC = peso / (altura * altura).

calculaMediaValida():

Ordena as notas, exclui a maior e a menor, e calcula a média das restantes.

*Métodos auxiliares (obtem)*:

Retornam os atributos ou cálculos do atleta:

obtemNomeAtleta()

obtemIdadeAtleta()

obtemPesoAtleta()

obtemNotasAtleta()

obtemCategoria()

obtemIMC()

obtemMediaValida()

Exemplo de Uso

O exemplo abaixo demonstra como criar um atleta e exibir as informações:
