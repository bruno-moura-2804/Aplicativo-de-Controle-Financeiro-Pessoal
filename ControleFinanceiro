import java.util.ArrayList;
import java.util.Date;

public class ControleFinanceiro {
    private ArrayList<Transacao> transacoes;

    public ControleFinanceiro() {
        this.transacoes = new ArrayList<>();
    }

    public void adicionarTransacao(double valor, String tipo, String descricao) {
        Transacao transacao = new Transacao(valor, tipo, descricao, new Date());
        transacoes.add(transacao);
    }

 
    public double calcularSaldo() {
        double saldo = 0;
        for (Transacao transacao : transacoes) {
            if (transacao.getTipo().equals("receita")) {
                saldo += transacao.getValor();
            } else if (transacao.getTipo().equals("despesa")) {
                saldo -= transacao.getValor();
            }
        }
        return saldo;
    }

    public void gerarRelatorio() {
        for (Transacao transacao : transacoes) {
            System.out.println(transacao);
        }
    }

    public void exibirSaldo() {
        System.out.println("Saldo atual: R$ " + calcularSaldo());
    }
}
