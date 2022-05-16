#media3notas
package exercicio3_02;
import java.util.Scanner;
public class exercicio3_02 {

	public static void main(String[] args) {
		Scanner ler = new Scanner(System.in);
		//Setando variáveis
		int a,RA;
		//Imprimindo frase perguntando se existe aluno
		System.out.printf("Existem alunos, digite 1 para sim e 2 para nao:\n");
		a=ler.nextInt();
		//If para acabar com o codigo caso não tenha alunos ou se tiver ele pede o RA
		if (a==1)
			//Imprimindo que existem alunos
			System.out.print("Existem alunos\n");
		    //Pedindo o RA do aluno
		    System.out.print("Digite o RA do aluno:\n");
		    //Lendo o numero digitado
		    RA=ler.nextInt();
		    if (RA==0)
		    	//Informando que o código acabou
		    	System.out.printf("Sistema encerrado");
		    //Else para o codigo continuar
		    else		    
		    	//Pedindo a nota 1 do aluno
		    System.out.print("Digite a primeira nota do aluno:\n");
		    //Setando variáveis
		    float nota1,nota2,nota3;
		    //Lendo a nota do aluno
		    nota1=ler.nextInt();
		  //Pedindo a nota 2 do aluno
		    System.out.print("Digite a segunda nota do aluno:\n");
		    //Lendo a nota do aluno
		    nota2=ler.nextInt();
		  //Pedindo a nota 3 do aluno
		    System.out.print("Digite a terceira nota do aluno:\n");
		    nota3=ler.nextInt();
		    //Setando variável
		    float soma;
		    //Dando objetivo para a variável, calcular a soma de tudo
		    soma=nota1+nota2+nota3;
		    //Imprimindo o valor da media
		    System.out.printf("Media igual a %f",soma/3);
		    //If para determinar dependendo da media se o aluno está aprovado
		    if (soma>=8)
		    	//Imprimindo que o aluno está aprovado
		    	System.out.print("\nAluno aprovado");
		    //Se não, se a media dele for maior que 6 e menor que 8 ele está de recuperação
		    else if (soma>6 || soma<8)
		    	//Imprimindo que ele esta de recuperação
		    	System.out.print("\nAluno de recuperação");
		    //Se não, se a media do aluno for menor que 6 ele está reprovado
		    else if (soma<6)
		    	//Imprimindo que o aluno foi reprovado
		    	System.out.print("\nAluno reprovado");
		    
	
		

	}

}
