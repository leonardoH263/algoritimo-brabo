# algoritimo-brabo

ESCREVA("Digite a cotação do dólar");
LEIA(numero1);
ESCREVA("Digite o valor desejado para a conversão");
LEIA(numero2);
resultado<-numero1*numero2;

SE(numero2<10) ENTAO
	ESCREVA("Não é possível fazer conversão. O numero convertido deve ser maior que 10");
SENAO
  	SE(numero2 = 10) ENTAO
		  ESCREVA("O resultado é:");
	  		ESCREVA(resultado);
SENAO

		    ESCREVA("O resultado é:");
	    		 ESCREVA(resultado);
	FIM-SE

FIM-SE
