Curso JavaScript Ninja

Aula 01
'Variáves - Tipos de Dados'
	var = valor_da_variavel
Number = Números
String = Escrita, Caracteres
Boolean = True ou False
Null = Nenhum valor
Undefined = Parecido com null, ausência de valor

object {} = definir objeto e suas propriedades dentro da mesma variavel (objeto.propriedades)
	var = casa {teto:'branco',parede:'verde'}
	ler: casa.teto , substituir casa.teto = 1
array [] = lista de valores (variavel[Indice])
	var = casa [1,2,3,4,5,6]

'Operadores Aritméticos'
+ Adição
- Subtração
* Multiplicação
/ Divisão

'Operadores Aritméticos Abreviados'
++ (adiciona +1)
-- (subtrai 1)
	Exemplo: soma++; || soma --;

+= (pega o valor da variavel + o que adicionar)
-= (pega o valor da variavel - o que subtrair)
*= (pega o valor da variavel * o que multiplicar)
/= (pega o valor da variavel / o que dividir)
	Exemplo: soma += 10;

Exemplo:
soma++;
soma += 10;

'Operadores de igualdade e relacionais'
== Igual a
!= Diferente de

=== Igual a, e do mesmo tipo de dado
!== Diferente, mas do mesmo tipo de dado

> Maior que
< Menor que
>= Maior ou igual a
<= Menos ou igual a

'Funções'
Blocos de código Javascript nomeados, e que podem ser invocados usando o operador ().
function nome() {}

Funções criam escopo, sem return não é possível chamar as variáveis declaradas dentro da função.

'Return' 
Retornar valores dentro das funções
Exemplo:
	function soma() {
		fernando = 'fernando';
		return fernando;
	}
	Pelo return consigo acessar a variável fora da função.

Funções podem receber argumentos ou parâmetros
Exemplo:
	function soma (x, y) {
		return x + y;
	}


-----------------------------------------------

