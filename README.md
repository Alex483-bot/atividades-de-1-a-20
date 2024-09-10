import java.util.Scanner;

// primeiro exercicio sobre divisao
class Main {
  public static void main(String[] args) {
  
  	Scanner valor = new Scanner(System.in);
    
  int primeiro, segundo, divisao, resto;

  
  System.out.println("Digite o valor do primeiro número");
  primeiro = valor.nextInt();
  
  System.out.println("Digite o valor do segundo número");
  segundo = valor.nextInt();
  
  resto = primeiro % segundo;
  System.out.println("O resto da divisão entre eles é" +resto);
    valor.close();
    
  
    
  }
}
