# Estudo de Caso Aplicado :open_file_folder:

*Soma de um intervalo* - Aplicação de Pensamento Computacional 

Ex.: Soma de **n** entre **1 e 200** 



1. Passo 1 - Recebe os valores (x e y)
2. Passo 2 - Resolva: 
3. ​		      y/2 = total 
4. Passo 3 - Resolva:
5. ​             y+x = resultado_parcial 
6. Passo 4 - Ache o total 
7. ​			Final = total x resultado_parcial
8. Passo 5 - Imprima o resultado 

------

```
programa {
	funcao inicio() {
		inteiro x, y 
		
		escreva("Digite os números para executar a soma do intervalo")
		leia(x)
		leia(y)
		
		escreva(soma_intervalo(x,y))
		
	}
	funcao inteiro soma_intervalo(inteiro x, inteiro y){
	    inteiro total, resultado_parcial 
	    total = y/2 
	    resultado_parcial = y+x 
	    
	    inteiro resultado = total * resultado_parcial 
	    retorne resultado
	}
}

```

