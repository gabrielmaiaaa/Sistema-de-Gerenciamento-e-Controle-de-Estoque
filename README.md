# Sistema-de-Gerenciamento-e-Controle-de-Estoque

**Projeto dessenvolvido por alunos da UNIFEI, Universidade Federal de Itajubá, da discíplina de OOP.**

<div>
  <p>
    Neste trabalho cada grupo deverá implementar um sistema para gerenciamento devendas e controle de estoque de uma loja de confecções (roupas). No setor de estoque, as mercadorias adquiridas dos fornecedores são incluídas no estoque da loja. Cada mercadoria é identificada por um código numérico, uma descrição, um preço de compra e um valor de venda. Toda vez que um produto novo entra no estoque, ele deve ser cadastrado com as informações anteriores. Para produtos já cadastrados, basta fazer a atualização da quantidade em estoque. Por exemplo, se haviam 10 unidades do produto cujo código é 1234 e foram comprados 20 novas unidades, o total em estoque desse produto passa a ser de 30 unidades. Note que, por efeito de simplificação, o valor de compra e venda dos produtos se mantém constante.
  </p>
  <p>
    As vendas de confecções são sempre feitas com emissão de nota fiscal. Para emitir a nota, o cliente deve estar cadastrado no sistema. Assim, no processo de emissão da nota fiscal, deve ser solicitado o CPF do cliente. Caso o cliente não exista, ele deve ser cadastrado com nome, endereço e e-mail, além do CPF.
  </p>
  <p>
    Após a inserção do CPF do cliente, deve-se exibir seu nome. O passo seguinte consiste no lançamento dos produtos vendidos. Até 10 produtos diferentes podem ser incluídos em cada nota. Para cada produto, deve-se ler o código e a quantidade vendida. A descrição e o preço de venda do produto devem aparecer na interface após a digitação de um código válido. A digitação de um código inválido (produto inexistente) deve ser notificada por uma mensagem. Obviamente, um produto só pode ser vendido se existir em estoque na quantidade solicitada. Dessa forma, se for informada uma quantidade maior que a existente no estoque, deve-se dar uma mensagem apropriada e impedir que o usuário continue até que uma quantidade válida seja escolhida, ou até que o usuário escolha um produto que tenha quantidade suficiente em estoque. Quando terminar o procedimento de lançar produtos na nota, o usuário deve clicar em um botão para emitir a nota. Neste momento deve-se gerar um número único para a nota e os valores em estoque de cada produto devem ser atualizados. Deve haver também um botão que permita cancelar a emissão da nota. Neste caso, o estoque dos produtos incluídos não deve ser alterado. No momento da emissão da nota, deve-se informar seu valor total, ou seja, a soma do valor de venda de todos os produtos vendidos. Outra informação importante é a data da emissão da nota. Essa data deverá ser digitada no momento da criação da nota para facilitar o processo de correção do trabalho (o procedimento usual seria pegar a data atual do sistema).
  </p>
</div>

<div>
    <p>
    O controle de estoque e de venda permitirá construir um sistema de informação sobre o negócio. Deve ser possível:
  </p>
  <ol>
    <li>
      Consultar qualquer produto da loja a partir de seu código, exibindo seu estoque, descrição e preço de venda;
    </li>
    <li>
      Consultar clientes, a partir do CPF, exibindo o nome, endereço e email.
    </li>
    <li>
      Consultar o faturamento por produto, a partir de seu código;
    </li>
    <li>
      Consultar o faturamento por cliente, a partir de seu CPF;
    </li>
    <li>
      Consultar o faturamento por período, sendo fornecidas uma data inicial e uma data final que delimitam o período.
    </li>
    <li>
      Consultar o lucro líquido por período, sendo fornecidas uma data inicial e uma data final que delimitam o período.
    </li>
    <li>
      Consultar as vendas realizadas para um determinado cliente em um determinado período. Neste caso, deve-se solicitar o código do cliente e as datas inicial e finaldo período e listar o número das notas fiscais emitidas para o cliente. Para cada nota deve ser informado o valor total da mesma.
    </li>
    <li>
      Informar os 10 produtos mais vendidos, com código, descrição, preço de venda e total vendido.
    </li>
  </ol>
</div>

<div>
    <h3>Importante:</h3>
  <ul>
    <li>
      O sistema deve ser implementado seguindo o modelo MVC. 
    </li>
    <li>
      As informações sobre produtos, clientes e vendas devem ser persistidas em arquivos.
    </li>
    <li>
      Para facilitar a correção, deve-se embutir um código que faça o cadastramento de 10 produtos, todos com estoque de 10 unidades.
    </li>
  </ul>
</div>
