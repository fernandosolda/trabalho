# trabalho
Algoritmo "aumento de funcioanrio"
// Disciplina: [PA] //
Professor: cintia pinho //
Descrição: cálculo o imposto de renda (função) //
Autor (a): Luís Fernando Osuna Solda
// Dados atuais: 27/09/2021
Var
salario, resp: real
Inicio escreval 
("qual seu salario?")
leia (salario)
se (salario &lt;= 1500) entao 
resp &lt;- salario * 1.20
fimse 
se ((salario> = 1500) e (salario &lt;= 3000)) entao  
resp &lt;-salario * 1,15
fimse
se ((salario> 3000) entao
resp &lt;-salario * 1,10 
fimse
escreval 
("o seu salario com aumento sera de:", resp)
Fimalgoritmo 
