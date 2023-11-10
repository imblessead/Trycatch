# Trycatch
Trycatch

package exemplos;

public class ExemploTryCatch {

	public static void main(String[] args) {
		try {
			int data=100/0;
			System.out.println(data);
		} catch (Exception e) {
			System.out.println("Nao e possivel efetuar a divisao por 0");
		}	

	}

}
