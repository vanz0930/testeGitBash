# WELCOME :+1:
### Test Ruby code
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```  
> 06/11/2017  
### Test Java Code
```java
public class HelloWorld
{
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

### Test JS code
```javascript
var x=window.confirm("Are you sure you want to quit")

if (x)
    window.alert("Thank you.")
else
    window.alert("Good choice.")
```
### Test C code
```c
#include <stdio.h>
#include <stdlib.h>


int main ()

{
	int capmax, codigo, lugdisp, entrou, saiu;
	char decisao;
	
	capmax = 10;
	entrou = 0;
	saiu = 0;
	lugdisp = capmax;
		
	printf ("Insira o codigo da operacao: ");
	scanf ("%d", &codigo);
	
	while (codigo != 0){
    
    	switch (codigo) {
    		case 1:
    		if (lugdisp != 0){
			printf ("Entrou \n");
			lugdisp = lugdisp - 1;
			entrou = entrou + 1;
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			else {
			printf ("Restaurante lotado! \n");
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			break;
		
			case 2:
    		if (lugdisp < 10){
			printf ("Saiu \n");
			lugdisp = lugdisp + 1;
			saiu = saiu + 1;
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);	
			}
			else {
			printf ("Nao ha clientes no momento! \n");
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			break;
		
			case 3:
			printf ("Lugares dispniveis: %d \n", lugdisp);
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			break;
		
			case 4:
			if (entrou == 1){
			printf ("Entrou %d pessoa! \n", entrou);
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			else {
			printf ("Entraram %d pessoas \n", entrou);
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			break;
		
			case 5:
			if (saiu == 1){
			printf ("Saiu %d pessoa! \n", saiu);
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			else {	
			printf ("Sairam %d pessoas! \n", saiu);
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			}
			break;
		
			default:
			printf ("Codigo invalido! \n");
			fflush(stdin);
			printf ("Insira o codigo da operacao: ");
			scanf ("%d", &codigo);
			break;
    	}
	}
    //printf ("Deseja encerrar o programa? \n");
    //scanf ("%ch", decisao);
	//if (decisao == 'N'){
	//fflush(stdin);
	//printf ("Insira o codigo da operacao: ");
	//scanf ("%d", &codigo);
	//}
	//else {
	//system ("pause");
    //return 0; // encerra o programa
	//}
	    
	system ("pause");
    return 0; // encerra o programa
	
}

```
