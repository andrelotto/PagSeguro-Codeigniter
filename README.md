PagSeguro-Codeigniter
=====================

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5e949c39811044498e07dbea3b4d7abb)](https://www.codacy.com/app/andrelotto/PagSeguro-Codeigniter?utm_source=github.com&utm_medium=referral&utm_content=andrelotto/PagSeguro-Codeigniter&utm_campaign=badger)


Biblioteca de integração com PagSeguro para Codeigniter.

<h2>Como utilizar</h2>
<p>Veja o controller/exemplo_ps</p>

<p>Dados do cliente</p>
<code>$this->pagseguro->set_user($usuario);</code>

<p>Dados dos produtos</p>
<code>$this->pagseguro->set_products($products);</code>

<p>Identificador do pedido</p>
<code>$config['reference'] = '999';</code>

<p>Gera botão de pagamento</p>
<code>echo $this->pagseguro->get_button($config);</code>

<p>Para mais opções de configuração veja em 'libraries/Pagseguro.php'</p>