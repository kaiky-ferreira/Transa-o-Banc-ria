import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner teclado = new Scanner(System.in);    

        Conta pedro = new Conta(23214, 100);
        Conta davi = new Conta(12345, 100);

        System.out.println("Digite o valor a ser transferido de Pedro para Davi: ");
        double valorTransferencia = teclado.nextDouble();

        Transacao transacao = new Transacao(pedro, davi, valorTransferencia);
        transacao.realizarTransacao();

        System.out.println("Saldo da conta Pedro: " + pedro.getSaldo());
        System.out.println("Saldo da conta Davi: " + davi.getSaldo());

        teclado.close();
    }
}
