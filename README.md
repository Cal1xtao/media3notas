# media3notas
package exercicio3_02;
import java.util.Scanner;
public class exercicio3_02 {

	public static void main(String[] args) {
		Scanner ler = new Scanner(System.in);
		int a,RA;
		System.out.printf("Existem alunos, digite 1 para sim e 2 para nao:\n");
		a=ler.nextInt();
		if (a==1)
			System.out.print("Existem alunos\n");
		    System.out.print("Digite o RA do aluno:\n");
		    RA=ler.nextInt();
		    if (RA==0)
		    	System.out.printf("Sistema encerrado");
		    else
		    System.out.print("Digite a primeira nota do aluno:\n");
		    float nota1,nota2,nota3;
		    nota1=ler.nextInt();
		    System.out.print("Digite a segunda nota do aluno:\n");
		    nota2=ler.nextInt();
		    System.out.print("Digite a terceira nota do aluno:\n");
		    nota3=ler.nextInt();
		    float soma;
		    soma=nota1+nota2+nota3;
		    System.out.printf("Media igual a %f",soma/3);
		    if (soma>=8)
		    	System.out.print("\nAluno aprovado");
		    else if (soma>6 || soma<8)
		    	System.out.print("\nAluno de recuperação");
		    else if (soma<6)
		    	System.out.print("\nAluno reprovado");
		    
	
		

	}

}
![Media3notas](https://user-images.githubusercontent.com/101893557/168134381-ef1054af-e9f7-4aa7-a60a-163e90f4e656.jpeg)
