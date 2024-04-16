import java.time.LocalDate;

class Transacao {
    private Conta origem;
    private Conta destino;
    private LocalDate data;
    private double valor;

    public Transacao(Conta origem, Conta destino, double valor) {
        this.origem = origem;
        this.destino = destino;
        this.valor = valor;
        this.data = LocalDate.now();
    }

    public void realizarTransacao() {
        if (origem.contaDebito(valor)) {
            System.out.println(data);
            destino.contaCredito(valor);
            System.out.println("Transação realizada com sucesso!");
          
        } else {
            System.out.println("Saldo insuficiente na conta de origem.");
        }
    }
}
