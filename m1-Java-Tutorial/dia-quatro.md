# Java Short Hand If...Else (usando operador ternário)

sintaxe é:

variavel = (condição) ? seForVerdade : seForFalso;

```
int time = 12;

String resultado = (time < 12) ? "Bom dia" : "Boa Tarde";

System.out.println(resultado); 

```

# Java Switch

Switch significa trocar, parece que está relacionado a uma escolha.
Break - pausa o código naquele bloco

Exemplo:
```
int dia = 4;

switch(dia) {
    case 1:
        System.out.println("Segunda");
    break;
    case 2:
        System.out.println("Terça");
    break
    case 3:
        System.out.println("Quarta");
    break;        
    case 4:
        System.out.println("Quinta");
    break;       
}

```

# Java While Loop

while é igual enquanto... então seria enquanto tal condição acontecer irá rodar o loop

consigo pensar em algo no sentido de, enquanto um numero for < 10 então incrementa em 1

```
while (condição) {
    //executa esse código
}
```

tem do DO e while

```
int number = 0;
do {
    System.out.println(number);
    number++; // aqui acontece um incremento
}
while (number < 10);
```