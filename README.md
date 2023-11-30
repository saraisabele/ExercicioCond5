# ExercicioCond5
# programa que realiza a leitura de um pedido e calcula o valor total da compra

  package exercicioCond5;
  import java.util.Scanner;
  
  public class leituraCardapio {
  	public static void main(String[] args) {
  		Scanner sc  = new Scanner(System.in);
  		
  		System.out.println("Digite o código do item que deseja: ");
  		double codigo = sc.nextDouble();
  		System.out.println("Digite a quantidade desse item que deseja: ");
  		double quantidade = sc.nextDouble();
  		
  		Double TotalConta;
  
  		if(codigo == 1) {
  			TotalConta = 4.0 * quantidade;
  			System.out.println("Total: R$ " + TotalConta);	
  		}
  		else if(codigo == 2) {
  				TotalConta = 4.5 * quantidade;
  				System.out.println("Total: R$ " + TotalConta);
  		}
  		else if (codigo == 3) {
  			TotalConta = 5.0 * quantidade;
  				System.out.println("Total: R$ " + TotalConta);
  		}
  		else if(codigo == 4.0) {
  			TotalConta = 2 * quantidade;
  			System.out.println("Total: R$" + TotalConta);
  		}
  		else if(codigo == 5.0) {
  			TotalConta = 1.5 * quantidade;
  			System.out.println("Total: R$ " + TotalConta);
  		}
  		sc.close();
  		}
  			
  	}
