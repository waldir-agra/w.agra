# w.agra
Estudos POO em JAVA

Q1
package lista1;

import java.util.Scanner;

public class q1 {
	public static void main(String[]ars){
		Scanner sc = new Scanner(System.in);
		int a ,b ,c, delta ;
		double x1,x2;
		
				
		System.out.println("Digite o valor de A: ");
		a = sc.nextInt();
		
		System.out.println("Digite o valor de B: ");
		b = sc.nextInt();
		
		System.out.println("Digite o valor de C: ");
		c = sc.nextInt();
		delta = ((b*b)-(4*a*c));
		x1 = 0;
		x2 = 0;		
		
		if(delta==0) {
			System.out.println("Há uma raiz real");
			x1=(-b)/(2*a);
			System.out.println("X! = " + x1);
		}
		if(delta > 0) {
			System.out.println("Existem duas raizes reais:");
			x1= ((-b + Math.sqrt(delta)) / (2*a));
			x2=((-b - Math.sqrt(delta)) / (2*a));
			System.out.println("x1 vale :" +x1);
			System.out.println("x2 vale :" +x2);
		} 
		else {
			System.out.println("Delta invalido! ");
		}
	}

}








Q2
package lista1;

public class q2 {
	public static void main(String[]args) {
		boolean a=true;
		boolean b=true;
		boolean c=false;
		
		if(a==true) {
			System.out.println("comando1");
		}else {
			if(b==true) {
				if(c==true) {
					System.out.println("comando2");
				}else {
					System.out.println("comando3");
					System.out.println("comando4");
				}
			}
		System.out.println("comando5 "); 
	}
	System.out.println("comando6");
	}
}



A
B
C
resposta
V
V
F
Comando 1 e 6
F
V
V
Comando 2,5,6
F
V
V
Comando 2,5,6
F
F
V
Comando 5 e 6



N ha resposta


Q3

	

