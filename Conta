class Conta {
    private int id;
    private double saldo;

    public Conta(int id, double saldo) {
        this.id = id;
        this.saldo = saldo;
    }

    public double getSaldo() {
        return saldo;
    }

    public boolean contaDebito(double debito) {
        if (debito > saldo) {
            return false;
        } else {
            saldo -= debito;
            return true;
        }
    }

    public void contaCredito(double credito) {
        saldo += credito;
    }
}
