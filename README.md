# desafio4
# exercicio 1 
        int idade;
        Scanner ler = new Scanner(System.in);
        System.out.println("qual sua idade?");
        idade = ler.nextInt();
        if (idade >= 5 && idade <= 7) {
            System.out.println("categoria: infantil A");
        } else if (idade >= 8 && idade <= 10) {
            System.out.println("categoria: infantil B");
        } else if (idade >= 11 && idade <= 13) {
            System.out.println("categoria: Juvenil A");
        } else if (idade >= 14 && idade <= 17) {
            System.out.println("categoria: juvenil B");
        } else if (idade >= 18) {
            System.out.println("categoria: adulto");
        } else {
            System.out.println("nao tem idade suficiente");

        }

    }

    }

# Exercicio 2
    //Declaração das variáveis
    double produto, produtoDesconto;
    Scanner ler = new Scanner (System.in);
    
    //Entrada de dados 
    System.out.println("Digite o valor do produto: ");
    produto = ler.nextDouble();
    
    //Processamento e saída de dados
    if ( produto > 0 && produto <= 100) {
        produtoDesconto = produto * 0.95;
        System.out.println("Valor final do produto: "+produtoDesconto);
    } else if ( produto >= 100) {
        produtoDesconto = produto * 0.85;
        System.out.println("Valor final do produto: "+produtoDesconto);
    } else {
        System.out.println("VALOR INVÁLIDO");

# Exercicio 3
        Scanner ler = new Scanner(System.in);
        System.out.println("qual o horario? ");
        hora = ler.nextInt();
        if(hora >= 0 && hora<= 11){
            System.out.println("Bom dia!");
        } else if(hora >= 12 && hora <= 18){
            System.out.println("Boa tarde!");
        }else if(hora >= 19 && hora <=23){
            System.out.println("Boa noite!");
        }

    }

    }

# Exercicio 4
        int nota;
        Scanner ler = new Scanner(System.in);
        System.out.println("qual a nota?");
        nota = ler.nextInt();
        if(nota >= 0 && nota < 50){
            System.out.println("INSUFICIENTE!");
        }else if(nota >= 50 && nota < 70){
            System.out.println("REGULAR");
        }else if (nota >= 70 && nota < 90){
            System.out.println("BOM");
        }else if (nota > 89 && nota <= 100){
            System.out.println("EXELENTE");
        } else {
            System.out.println("nota invalida, apenas de 0 a 100!");
        }
    }
    
    }

# vExercicio 5
        double valorA, valorB, valorC;
        Scanner ler = new Scanner(System.in);
        System.out.println("digite um valor");
        valorA = ler.nextDouble();
        System.out.println("digite outro valor");
        valorB = ler.nextDouble();
        System.out.println("digite mais um valor");
        valorC = ler.nextDouble();
        
        if (valorA == valorB && valorA == valorC ){
            System.out.println("triangulo equilatero ");
        } else if (valorA != valorB && valorA != valorC){
            System.out.println("triangulo escaleno");
        } else {
            System.out.println("triangulo isóceles");
            
        }
        
        
        
        
    }

    }

















# Exercicio 6
        double baseMaior, baseMenor, altura, A;
        Scanner ler = new Scanner(System.in);
        System.out.println("qual o valor da base maior?");
        baseMaior = ler.nextDouble();
        System.out.println("qual o valor da base menor?");
        baseMenor = ler.nextDouble();
        System.out.println("qual o valor da altura?");
        altura = ler.nextDouble();
        if (baseMaior > 0 && baseMenor > 0) {
            A = ((baseMaior + baseMenor) * altura) / 2;
            System.out.println("a area do trapézio é: " + A);
        } else {
            System.out.println("valor invalido!! apenas numeros maiores que 0");

        }
    }

    }

# Exercicio 7
    double a, b, c, delta, raiz1, raiz2;
    Scanner ler = new Scanner(System.in);

    System.out.println("Digite o valor de A");
    a = ler.nextDouble();

    if ((a == 0)) {
        System.out.println("O valor de A não pode ser igual a 0");
    } else {
        System.out.println("Digie o valor de B");
        b = ler.nextDouble();
        System.out.println("Digite o valor de C");
        c = ler.nextDouble();

        delta = (b * b) - (4 * a * c);

        if (delta > 0) {

            raiz1 = (-b + Math.sqrt(delta)) / (2 * a);
            raiz2 = (-b - Math.sqrt(delta)) / (2 * a);
            System.out.println("As raizes são reais e distintas:");
            System.out.println("Raiz 1: " + raiz1);
            System.out.println("Raiz 2: " + raiz2);
        } else if (delta == 0) {

            raiz1 = -b / (2 * a);
            System.out.println("A equação possui uma unica raiz real:");
            System.out.println("Raiz: " + raiz1);
        } else {
            System.out.println("A equação não possui razes reais.");

# Exercicio 8
       int dia;
       Scanner ler = new Scanner (System.in);
        System.out.println("digite o número do dia da semana");
        dia = ler.nextInt();
        switch(dia){
            case 1:
                System.out.println("Segunda-Feira");
                break;
            case 2:
                System.out.println("Terça-Feira");
                break;
            case 3:
                System.out.println("Quarta-Feira");
                break;
            case 4:
                System.out.println("Quinta-Feira");
                break;
            case 5:
                System.out.println("Sexta-Feira");
                break;
            case 6:
                System.out.println("Sábado");
                break;
            case 7:
                System.out.println("Domingo");
                break;
                default:
                    System.out.println("dia invalido");
                    break;
                
                
        }
    }
    }

# Exercicio 9
    int mes;
    Scanner ler = new Scanner (System.in);
    
    System.out.println("Digite um número para saber o mês: ");
    mes = ler.nextInt();
    
    switch (mes) {
        case 1 : 
            System.out.println("Janeiro");
            break;
        case 2: 
            System.out.println("Fevereiro");
            break;
        case 3:
            System.out.println("Março");
            break;
        case 4:
            System.out.println("Abril");
            break;
        case 5: 
            System.out.println("Maio");
            break;
        case 6:
            System.out.println("Junho");
            break;
        case 7: 
            System.out.println("Julho"); 
            break;
        case 8:
            System.out.println("Agosto");
            break;
        case 9: 
            System.out.println("Setembro");
            break;
        case 10:
            System.out.println("Outubro");
            break;
        case 11:
            System.out.println("Novembro");
            break;
        case 12:
            System.out.println("Dezembro");
            break;
        default:
            System.out.println("Mês inválido");
            break;


# Exercicio 10
    int mes;
    Scanner ler = new Scanner (System.in);
    
    System.out.println("Digite um número do mês: ");
    mes = ler.nextInt();
    
    switch (mes) {
        case 12: 
        case 1: 
        case 2: 
            System.out.println("Estação: verão");
            break;
        case 3: 
        case 4: l
        case 5:
            System.out.println("Estação: outono");
            break;
        case 6: 
        case 7: 
        case 8: //
            System.out.println("Estação: inverno");
            break;
        case 9: 
        case 10: 
        case 11: 
            System.out.println("Estação: Primavera");
        default:
            System.out.println("Mês inválido");
