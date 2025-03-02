import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        ControleFinanceiro controle = new ControleFinanceiro();

        while (true) {
            System.out.println("\n--- Controle Financeiro ---");
            System.out.println("1. Adicionar Receita");
            System.out.println("2. Adicionar Despesa");
            System.out.println("3. Consultar Saldo");
            System.out.println("4. Gerar Relatório");
            System.out.println("5. Sair");
            System.out.print("Escolha uma opção: ");
            int opcao = scanner.nextInt();
            scanner.nextLine();  

            switch (opcao) {
                case 1:
                    System.out.print("Digite o valor da receita: R$ ");
                    double valorReceita = scanner.nextDouble();
                    scanner.nextLine();  // Consumir a quebra de linha
                    System.out.print("Digite a descrição da receita: ");
                    String descricaoReceita = scanner.nextLine();
                    controle.adicionarTransacao(valorReceita, "receita", descricaoReceita);
                    break;

                case 2:
                    System.out.print("Digite o valor da despesa: R$ ");
                    double valorDespesa = scanner.nextDouble();
                    scanner.nextLine();  // Consumir a quebra de linha
                    System.out.print("Digite a descrição da despesa: ");
                    String descricaoDespesa = scanner.nextLine();
                    controle.adicionarTransacao(valorDespesa, "despesa", descricaoDespesa);
                    break;

                case 3:
                    controle.exibirSaldo();
                    break;

                case 4:
                    controle.gerarRelatorio();
                    break;

                case 5:
                    System.out.println("Saindo...");
                    scanner.close();
                    return;

                default:
                    System.out.println("Opção inválida! Tente novamente.");
                    break;
            }
        }
    }
}

