# Lista-02---Estruturas-Condicionais
- Exercicio 1
<img width="739" height="413" alt="image" src="https://github.com/user-attachments/assets/59fc5f6f-7284-4f66-a931-6395744a291e" />
- Exercicio 2
<img width="965" height="510" alt="image" src="https://github.com/user-attachments/assets/7b32df38-d5b3-4e45-b238-5ec2d0d76464" />
- Exercicio 3
<img width="951" height="509" alt="image" src="https://github.com/user-attachments/assets/ce242b06-a477-4bd3-b0c2-3f75ed6a1052" />
- Exericio 4
<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/f94ac471-ad99-4cb4-8ecc-939b0fd2fdfe" />
- Exercicio 5
<img width="885" height="505" alt="image" src="https://github.com/user-attachments/assets/eb37cabc-0445-4138-b298-9d7f6f0a8821" />
- Exercicio 6
<img width="908" height="506" alt="image" src="https://github.com/user-attachments/assets/a1f9fac3-cec0-4334-8d72-6e5d7b1f94bd" />
- Exrcicio 7
<img width="722" height="505" alt="image" src="https://github.com/user-attachments/assets/4f5bbea4-c088-4bc8-acc9-f1c1a23d6ae1" />
- Exercicio 8
import java.util.Scanner;

public class Exercicio08 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite o valor do salário: R$ ");
        double salario = scanner.nextDouble();
        
        System.out.print("Digite o valor da prestação mensal: R$ ");
        double prestacao = scanner.nextDouble();
        
        double limiteSalarial = salario * 0.30;
        
        if (prestacao <= limiteSalarial) {
            System.out.println("Financiamento APROVADO! O limite de 30% é R$ " + limiteSalarial);
        } else {
            System.out.println("Financiamento REPROVADO! A prestação excede os 30% do salário (R$ " + limiteSalarial + ").");
        }
        
        scanner.close();
    }
}
