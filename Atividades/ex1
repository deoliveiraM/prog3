<?php 

class Produto {
    public $nome;
    public $preco;
    public $quantidade;
    
    public function exibirInformacoes() {
        echo "Nome: {$this->nome}, Preço: {$this->preco}, Quantidade: {$this->quantidade}\n";
    }

    public function mostrarMediaPreco() {
        $mediaPreco = $this->preco / $this->quantidade;
        echo "Média de Preço: {$mediaPreco}\n";
    }
   
}


$produto1 = new Produto();
$produto1->nome = "Caneta";
$produto1->preco = 2.5;
$produto1->quantidade = 10;
$produto1->exibirInformacoes();
$produto1->mostrarMediaPreco();

$produto2 = new Produto();
$produto2->nome = "Borracha";
$produto2->preco = 0.8;
$produto2->quantidade = 15;
$produto2->exibirInformacoes();
$produto2->mostrarMediaPreco();
?>