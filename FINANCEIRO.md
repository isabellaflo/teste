<b>ÍNDICE:</b>

[1. ANÁLISE DE CRÉDITO](#analise)<br>
[2. BANCOS](#bancos)<br>
[3. BOLETOS](#boletos)<br>
[4. CAIXA - APURAÇÃO](#caixaapuração)<br>
[5. CAIXA - ENTRADAS](#caixaentradas)<br>
[6. CAIXA - SAÍDAS](#caixasaídas)<br>
[7. CENTRO DE CUSTOS](#centrodecustos)<br>
[8. CONDIÇÕES DE PAGAMENTOS](#condiçõesdepagamentos)<br>
[9. CONTAS A PAGAR](#contasapagar)<br>
[10. CONTAS A RECEBER](#contasareceber)<br>
[11. CONTAS FINANCEIRAS](#contasfinanceiras)<br>
[12. CRÉDITO COMERCIAL](#créditocomercial)<br>
[13. DARF](#darf)<br>
[14. DESPESAS FIXAS](#despesasfixas)<br>
[15. DESPESAS RECORRENTES](#despesasrecorrentes)<br>
[16. FORMAS DE PAGAMENTOS](#formasdepagamentos)<br>
[17. LOGS FINANCEIROS](#logsfinanceiros)<br>
[18. PASTAS](#pastas)<br>
[19. PLANO DE CONTAS](#planodecontas)<br>
[20. RECEITAS FIXAS](#receitasfixas)<br>
[21. REMESSA DE BOLETOS](#remessadeboleto)<br>
[22. RETORNO DE BOLETOS](#retornodeboleto)<br>
[23. TABELA IR](#tabelair)<br>
[24. TRANSFERÊNCIAS](#transferências)<br>
[25. RELATÓRIOS](#relatórios)<br>
[R. BOLETOS](#rboletos)<br>
[R. CONTAS A PAGAR](#rcontasapagar)<br>
[R. CONTAS A RECEBER](#rcontasareceber)<br>
[R. EXTRATO DE CONTAS](#rextratodecontas)<br>
[R. EXTRATO DE MENSALISTAS](#rextratodemensalistas)<br>
[R. FECHAMENTO DE CAIXA](#rfechamentodecaixa)<br>
[R. LIVRO AUXILIAR](#rlivroauxiliar)<br>
[R. LIVRO CAIXA](#rlivrocaixa)<br>
[R. PLANO DE CONTAS](#rplanodecontas)<br>
[R. RECEITA DIÁRIA](#rreceitadiária)<br>

<p align="center"><b>FINANCEIRO</b></p>


*Caso o cartório trabalhe com controle de senhas através de dispensador manual, impressora de senha ou totem de atendimento, o Acsiv possui um módulo específico para isso. Entre em contato com nosso suporte técnico para solicitar  a configuração.*

Vamos demonstrar o uso do formulário Financeiro, pesquisando informações, inserindo novo cadastro, alterando cadastro existente, excluindo registros, emitindo listagem e relatórios.

O objetivo será explicar os campos que compõe esse formulário, demonstrando com informações fictícias.

<div align="center">
<img src="https://user-images.githubusercontent.com/98952804/165134558-1afde495-4ba3-4c4e-a538-123d637abf9b.png" width="450px" />
</div>
<br></br>

<div id="analise" />
<b>1. Análise de crédito</b>
<br></br>

Análise de crédito <i>(Menu > Financeiro > Análise de crédito)</i> pode ser utilizada como uma análise de crédito dos mensalistas do cartório. Bastando cadastrar um limite de crédito e informar o nível de risco de habilitar crédito para determinado cliente.

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/2_Analise_De_Credito.PNG" width="700" />
</div>

**a. Cedente:** Funcionário que realizou a análise de crédito.

**b. Tomador:** Mensalista <i>(Cliente)</i> analisado.

**c.  Análise:**  Analisa a situação do mensalista <i>(Cliente)</i> antes de liberar o crédito.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/2_1.png" /> Selecionar as consultas realizadas durante a análise do cliente <i>(Mensalista)</i>.

**d. Nível de risco:**  O nível de risco varia de 0 a 9, sendo 0 muito seguro habilitar crédito e 9 muito arriscado. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/2_2.png" /> Crédito habilitado do nível de risco, é possível habilitar o crédito.

**e. Limite de crédito:**  Valor a liberar de crédito ao mensalista <i>(Cliente)</i>.

**f. Limite parcela:**  Limite da parcela a liberar ao mensalista <i>(Cliente)</i>.

**g. Observações:** É possível colocar alguma observação referente ao cliente <i>(Mensalista)</i>.
<br></br>


<div id="bancos" />
<b>2. Bancos</b>
<br></br>
Bancos <i>(Menu > Financeiro > Bancos)</i> é possível cadastrar banco, inserindo informações de número, dígito verificador e nome do banco.
<br></br>   
<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/3_Banco.PNG" width="700" />
</div>

**a. Número:**  Número do banco.

**b. Dígito verificador:**  Número do dígito verificador.

**c. Nome:** Nome do banco.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/3_1.png" /> É possível desativar o banco se necessário.
<br></br>

<div id="boletos" />
<b>3. Boletos</b>
<br></br>

Boletos <i>(Menu > Financeiro > Boletos)</i> utilizado quando o próprio cartório emite boletos. Ao salvar, o Acsiv cria um registro em contas a Receber.  

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/4_Boletos.PNG" width="700" />
</div>
<br>

**a. Dt. entrada:** Data automática do dia da entrada, mas poderá ser alterada caso necessário.

**b. Dt. vencimento:** Data automática do dia do vencimento, mas poderá ser alterada caso necessário.

**c. Valor:** Valor do boleto a ser gerado.

**d. Documento:** Opcional, se o cartório trabalhar com número de documento, preenche o campo, se não, pode deixar vazio.

**e. Func. resp.:** Funcionário que esta realizando a emissão do boleto.

**f. Devedor:** Utilizado para preencher o devedor do boleto.

**g. Plano de contas:** Escolhe o plano de contas que será efetivado a emissão do boleto.

**h. Histórico:** Preenche o histórico conforme necessário.

**i. Forma de pagto.:** Forma de pagamento que será pago o boleto.

**j. Conta:** Conta pela qual será creditado o boleto.
<br></br>

<div id="caixaapuração" />
<b>4. Caixa - Apuração</b>
<br></br>

Caixa - Apuração <i>(Menu > Financeiro > Caixa - Apuração)</i> Possível realizar abertura e fechamento do caixa do cartório.
<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Caixa_Apura%C3%A7%C3%A3o/1.PNG" width="700" />
</div>
<br>
Para abertura do caixa, basta selecionar <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Caixa_Apura%C3%A7%C3%A3o/Botao_Novo.PNG" />, como demonstrado a seguir:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Caixa_Apura%C3%A7%C3%A3o/1_1.PNG" />
<br></br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Conta:** Possível selecionar a conta a ser aberta.

**c. Situação:** Selecione qual a situação será realizada <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Caixa_Apura%C3%A7%C3%A3o/Bot%C3%A3o_Situacao.png" />. 
* Aberto: Para abertura da conta.
* Fechado: Para fechamento da conta. 

**d. Dt. lançamento:** Data do lançamento.

**e. Atendente:** Nome do funcionário responsável pela abertura/fechamento do caixa.

**f. Observações :** Observação referente a abertura/fechamento da conta.
<br></br>

<div id="caixaentradas" />
<b>5. Caixa - Entradas </b>
<br></br>

 Caixa - Entradas <i>(Menu > Financeiro > Caixa - Entradas)</i> Utilizado para realizar os lançamentos das receitas do cartório. <i><b>Ex.:</b> "Valores que entraram para o cartório".</i> 

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/5_Caixa_Entradas.PNG" width="700" />
</div>
<br>

**a. Dt. Vencimento:** Data vencimento do dia, mas poderá ser alterada caso necessário.

**b. Dt. entrada:** Data entrada do dia, mas poderá ser alterada caso necessário.

**c. Valor:** Valor a ser recebido.

**d. Documento:** Opcional, se o cartório trabalhar com número de documento, preenche o campo.

**e. Func. resp.:** Funcionário que esta realizando a entrada. 

**f. Devedor:** Nome do devedor.

**g. Plano de contas:** Selecione o plano de contas para o recebimento da entrada.

**h. Histórico:** Histórico conforme achar viável. <i><b>Ex:</b> Recebimentos diversos ref. mês 08/2021.</i>

**i. Forma de pagto.:** Forma de pagamento escolhida para realizada da entrada.

**j. Conta:** Conta escolhida para receber o valor da entrada.

**l. Dt. liquidação:** Data da efetivação do valor na conta do cartório. <i><b>Ex.:</b> Entrada realizada via pix programado para o dia seguinte, a data de liquidação, será o dia que foi liquidado na conta do cartório.</i> 

**m. N°controle:** Possível colocar o número de controle, se o cartório trabalhar com ele.
<br></br>


<div id="caixasaídas" />
<b>6. Caixa - Saídas </b>
<br></br>
Caixa - Saídas <i>(Menu - Financeiro - Caixas - Saídas)</i> Utilizado para realizar todas as saídas (despesas) do cartório. <i><b>Ex.:</b> "Valores que saíram do cartório".</i>  


<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/6_Caixa_Saidas.PNG" width="700" />
</div>
<br>

**a. Dt. vencimento:** Data vencimento do dia, mas poderá ser alterada caso necessário.

**b. saída:** Data saída do dia, mas poderá ser alterada caso necessário.

**c. Valor:** Valor da saída.

**d. Documento:** Opcional, se o cartório trabalhar com número de documento, preenche o campo.

**e. Func.resp.:** Selecione o funcionário responsável pelo registro da saída no sistema.

**f. Credor:**  Possível colocar o credor da saída. 

**g. Plano contas:** É possível selecionar o plano de contas para registro da saída.

**h. Histórico:** Histórico referente a saída, <i><b>ex.:</b>  Cemig ref. Mês 08/2021.</i> 

**i. Forma de pagto.:** Forma de pagamento que será realizada a saída.

**j. Conta:**  Conta que será realizado a saída.

**l. Dt. liquidação:**  Data da efetivação do valor na conta do cartório. <i><b>Ex.:</b> Saída realizada via Transferência bancária  programada para o dia seguinte, a data de liquidação, será o dia que foi liquidado na conta do cartório.</i>

**m. N° controle:**  Possível colocar o número de controle, se o cartório trabalhar com ele.
<br></br>


<div id="centrodecustos" />
<b>7. Centro de custos</b>
<br></br>
É utilizado para cadastrar algum centro de custo. <i>Ex.: cartório possui dois veículos, e quer ter controle sobre gastos/rendimento desses dois veículos. Nesse caso, eles poderiam cadastrar centros de custos, sendo as placas dos veículos.</i> Podemos acessar essa tela pelo <i>(Menu > Financeiro > Centro de custos)</i>.
<br></br>
<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_1.PNG" width="700" />
</div>
<br>

É possível pesquisar, criar um novo, abrir um centro de custos.

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_2.PNG" width="700" />
</div>
<br></br>

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_3.PNG" width="700" />
</div>
<br></br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Conta:** Conta criada no centro de custos.

**c. Descrição:** Neste exemplo foi utilizado a placa de um veículo para descrição.

**d. Conta superior:** Conta superior criada no Centro de custos.

Para desativar a conta, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/3_1.png" /> para concluir a operação.
<br></br>


<div id="condiçõesdepagamentos" />
<b>8. Condições de pagamentos</b>
<br></br>
Condições de pagamentos <i>(Menu > Financeiro > Condições de pagamentos)</i> utilizado somente em caso de parcelamentos. 

Ao abrir o formulário, é possível pesquisar, criar novas condições de pagamentos, abrir e excluir. 

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/8_Condicoes_Pagamentos_1.PNG" width="700" />
</div>
<br>

Exemplificando:

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/8_Condicoes_Pagamentos_2.PNG" width="700" />
</div>
<br>

**a. Código:**  Gerado automaticamente pelo sistema.

**b. Ordem:**  Ordem que será apresentado a condição de pagamento.

**c. Descrição:** Descrição do parcelamento <i><b>Ex.:</b></i> CARTEXPRESS.

**d. Vencimentos:**  Utilizado para colocar a forma que o pagamento deverá ocorrer. <i><b>Ex.:</b></i> 30/60/90 ou 0/15/45 dias.

**e. Fórmula:** Selecione entre os 5 fórmulas <i>(Nenhuma, Juro simples, Juro composto, Taxa de acréscimo, Taxa de desconto).</i> 

**f. Porcentual%:**  Percentual da condição de pagamento ao mês.

**g. Parcela mínima:** Valor da parcela mínima da condição do parcelamento.

**h. Ajuste de data:**  Ajuste de data. <i><b>Ex.:</b> 15 dias pra frente.</i> 
<br></br>


<div id="contasapagar" />
<b>9. Contas a pagar</b>
<br></br>
Contas a pagar <i>(Menu > Financeiro > Contas a pagar)</i>, será apresentado todas as contas a pagar do cartório.

É possível pesquisar os títulos por um credor em especifico ou apenas selecionar o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/pesquisar.PNG" /> para visualizar, como exemplo a seguir:

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_1.PNG" width="700" />
</div>
<br>

Vamos utilizar apenas dois credores para exemplificar.

Os títulos apresentados na tela na parte superior <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/N%C3%A3o_Quitados.PNG" /> significa que são títulos em abertos que não foram quitados ainda, após quitar, o mesmo aparecerá na parte inferior da tela <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Quitados.PNG" />. 

**a. Credor:** Credor da conta a pagar.

**b. Dt. vencimento:** Selecione entre ás 5 datas <i>(Vencimento, pagamento, programação, liquidação e lançamento).</i> 
<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/datas.png" />
</p>   

**c. Valor:** Ao clicar no campo Valor é possível alterar a opção de busca.
<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/valor.png" />
</p>

**d. Documento:** Campo utilizado para colocar informação do documento, não é campo obrigatório.


<div align="center"><i>Mostraremos algumas funcionalidades:</i></div>

***


<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/quitar.PNG" /> Botão realizado para quitar os títulos.

<p>
Selecione o título que deseja quitar.
 </p>
<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_2.PNG" />
</p>
<p>
Ao selecionar, será apresentado a seguinte tela:
</p>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_3.PNG" />
<br></br>
<p>
Assim que a conta for quitada, na tela de contas a pagar será apresentada da seguinte maneira:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_4.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/abrir.PNG" />  possível abrir a conta a pagar selecionada para ter acesso as informações.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_5.PNG" /><br><br>


<p align="center">
<i>Botão</i> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/14.png" width="50" />  <i>ferramentas (Atalho ALT + M), possui algumas funcionalidades, são elas:</i>     
</p>

---


<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Ferramentas_Pagar.png" />
</p>


* *Alteração de valores:*  Ao selecionar o título é possível alterar os valores.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_6.PNG" />
<br></br>

* *Alterações de vencimentos:*  É possível alterar os vencimentos dos títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_7.PNG" />
<br></br>

* *Desmembrar*: É possível desmembrar o título. *obs.:* Para desmembrar o título além de selecionar a parcela, o credor precisa esta selecionado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_8.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_9.PNG" />
<br></br>

* *Estornar:* É possível estornar um título que foi quitado indevidamente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_10.PNG" />
<br></br>
Após estornar, o título retorna para títulos não quitados.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_11.PNG" />
<br></br>

* *Excluir títulos:* Possível excluir títulos lançados indevidamente. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_12.PNG" />
<br></br>

* *Liquidar:*  Data que foi liquidada na conta do cartório.

* *Programar:* É possível programar a data que será quitado o título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_13.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_15.PNG" />
<br></br>

* *Taxas:* Possível definir a porcentagem da taxa, pelo <i>(Menu > Financeiro > Configurações > aba Contas a receber)</i></p>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Contas_apagar_configuracoes_taxas.PNG" />
<br></br>
Ao selecionar o título, é apresentado conforme imagem abaixo:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Contas_apagar_configuracoes_taxas_fim.PNG" />
<br></br>

* *Unificar:* É possível unificar dois títulos para pagar de uma só vez. *Obs.:* Precisa selecionar o credor antes de unificar os títulos conforme exemplo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_16.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_17.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_18.PNG" /><br>
<br></br>

<div id="contasareceber"/>
<b>10. Contas a receber</b>
<br></br>
Conseguimos localizar todas as contas a receber do cartório,  pelo <i>(Menu > Financeiro > Contas a receber).</i> 

A movimentação da tela conta a receber se dá através do lançamento do recibo com mensalista (*cliente*), mas podemos lançar o contas a receber direto nessa tela caso houver necessidade.



Detalharemos uma conta a receber através de um recibo para mensalista, pelo *(Menu > Cartório > Recibos)* para criar um novo recibo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/10_Recibo.PNG" />
<br></br>

Na forma de pagamento o mensalista esta selecionado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/10_Recibo_1.PNG" />
<br></br>

Como ficará esse recibo no contas a receber:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_1.PNG" />
<br></br>

Os títulos apresentados na tela na parte superior <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/N%C3%A3o_Quitados.PNG" /> significa que são títulos em abertos que não foram quitados ainda, após quitar, o mesmo aparecerá na parte inferior da tela <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Quitados.PNG" />.
<br></br>


<div align="center"><i>Mostraremos algumas funcionalidades:</i></div>

---



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/pesquisar.PNG" /> Pesquisa todas contas a receber do cartório. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/quitar.PNG" /> É possível quitar um ou mais títulos, conforme imagem a seguir:
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_2.PNG" />
<br></br>
Assim que a conta for quitada, na tela de contas a receber será apresentada da seguinte maneira:
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_3.png" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> Para criar um novo título direto do contas a receber.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/abrir.PNG" /> Possível abrir um título.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_4.PNG" />
<br></br>


<p align="center">
<i>Botão</i> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/14.png" width="50" />  <i>ferramentas (Atalho ALT + M), possui algumas funcionalidades, são elas:</i>     
</p>

---

<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Ferramentas_Receber.png" />
</p>
<br></br>

* *Alteração de valores:*  Ao selecionar o título é possível alterar os valores.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_5.PNG" />
<br></br>

* *Alteração de vencimentos:* Altera a data de vencimento do título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_6.PNG" />
<br></br>

* *Boletos:* Para emissão de boletos pelo sistema. 

**OBS:** *Para emitir boletos pelo sistema, precisa verificar se o banco é homologado no sistema, se sim, entrar em contato com o gerente do banco informando que gostaria de emitir boletos de terceiros.* 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_7.PNG" />
<br></br>

* *Desmembrar:* Utilizado para desmembrar títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_8.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_9.PNG" />
<br></br>

* *Duplicatas:* É possível gerar duplicatas referente ao título selecionado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_10.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_11.PNG" />
<br></br>

* *Estornar:* Pode-se estornar um título quitado.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_12.PNG " />
<br></br>

* *Excluir títulos:* É Possível excluir títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_13.PNG" />
<br></br>

* *Liquidar:* Há possibilidade de liquidar um título após quitado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_14.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_15.PNG" />
<br></br>

* *Notas promissórias:* É possível emitir notas promissórias dos títulos.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Notas_Promissorias_Contas_receber.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Notas_Promissorias_Contas_receber_Editado.PNG" />
<br></br>

* *Programar:* O sistema permite programar a data do recebimento do título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_16.PNG" />
<br></br>

Após programada a data, será apresentado na tela de contas a receber com a *Dt. Programação* preenchida.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_17.PNG" />
<br></br>

* *Recibos:* É Possível emitir um recibo do título que foi quitado.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Recibos_Contas_Receber.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Recibos_Contas_Receber_Emitido_Editado.PNG" />
<br></br>

* *Taxas:* É Possível configurar uma taxa caso seja necessário.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_18.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_19.PNG" />
<br></br>

* *Unificar:* É possível unificar títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_20.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_21.PNG" />
<br></br>


<div id="contasfinanceiras" />
<b>11. Contas financeiras</b>
<br></br>
Contas financeiras <i>(Menu > Financeiro > Contas financeiras)</i> , utilizado para realizar cadastro de conta financeira,  se for o caixa físico do cartório, basta marcar tipo <i>Caixa</i> e colocar o nome desejado. Se for banco, deve-se preencher algumas outras informações, conforme imagem a seguir:
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/12_Contas_Financeiras_1.PNG" />
<br></br>

**a. Código:**  Gerado automaticamente pelo sistema.

**b.Cartório:** Utilizado para colocar nome do cartório.

**c.Tipo:** Selecione entre os 2 tipos <i>(Caixa, Bancária)</i> , <b>ex.:</b> <i>Caixa físico do cartório ou banco</i>.

 **d.Conta:**  Pode-se colocar a conta do banco.

**e. Banco:** É possível colocar o nome do banco.

**f. Agência:** Pode-se colocar a agência.

**g. Limite de crédito:** Utilizado somente para conhecimento do usuário, caso queira consultar.

<p align="center">
<i>CHECKBOXES da tela:</i>     
</p>

---


<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_n%C3%A3o_fecha_caixa.PNG" /> Ao marcar essa opção, não será apresentado nenhum informação nos relatórios do financeiro.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_desativada.PNG" /> Ao marcar, será desativado essa conta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_emissao_de_boleto_autorizada.PNG" /> Quando o cartório trabalha com emissão de boletos, deve-se marcar o checkbox e preencher as informações conforme imagem abaixo. *OBS.: Essas informações são fornecidas pelo banco*. Mas se o cartório ainda não trabalha com emissão de boletos e gostaria de trabalhar. É necessário verificar se o banco é homologado,se sim, entrar em contato com o gerente, informar que quer emitir boleto de terceiros e solicitar as informações dos campos conforme imagem abaixo:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/12_Contas_Financeiras_2.PNG" />
<br></br>

**Aba Arquivos:** Só é preenchida depois que o aplicativo do banco estiver instalado na máquina.

**Aba Especial:** É preenchida quando a conta está em nome de pessoa jurídica, por exemplo, mas por alguma razão é necessário que o boleto saia no CPF.


<div id="créditocomercial" />
<b>12. Crédito comercial</b>
<br></br>
Crédito comercial <i>(Menu > Financeiro > Crédito comercial)</i>, funciona como uma espécie de pré-pago, o cliente<i>(Mensalista)</i> "compra créditos" antes de precisar usar.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/13_Credito_Comercial_1.PNG" />
<br></br>
Ao selecionar o histórico de créditos <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Historico_creditos.PNG" /> é possível verificar todo o histórico de crédito do cliente.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/13_Credito_Comercial_2.PNG" />
<br></br>

<div id="darf" />
<b>13. DARF</b>
<br></br>

Darf *(Menu > Financeiro > DARF)* -  *Sigla para Documento de Arrecadação de Receitas Federais*, pode- se emitir guia pelo sistema.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_1.PNG" />
<br></br>

Basta preencher os dados para emissão da guia, conforme imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_2.PNG" />
<br></br>

Ao finalizar o preenchimento dos campos, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Bot%C3%A3o_Visualizar.PNG" /> para imprimir a guia DARF.



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_3.PNG" width="400"/>
<br></br>

<div id="despesasfixas" />
<b>14. Despesas fixas</b>
<br></br>

Despesas fixas <i>(Menu > Financeiro > Despesas fixas)</i> <i><b>Ex.:</b> Carnê de pagamento em 12 parcelas vão para o contas a pagar</i>.

Em seguida, será apresentada a tela para preenchimento das despesas fixas. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_1.PNG" />
<br></br>

Com todas informações preenchidas, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" />.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_2.PNG" />
<br></br>

Agora, com as despesas fixas gerada será apresentada a seguinte tela:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_5.PNG" />
<br></br>

Clique novamente em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" /> para concluir a geração dos títulos.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_6.PNG" />
<br></br>

Para encontrar o lançamento dessa despesa <i>(Menu > Financeiro > Contas a pagar)</i> ,pesquise pelo nome do credor para encontrar os títulos.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_7.PNG" />
<br></br>

<div id="despesasrecorrentes" />
<b>15. Despesas recorrentes</b>
<br></br>

Despesas recorrentes <i>(Menu > Financeiro > Despesas recorrentes)</i>, é um facilitador das despesas fixas anuais. <b><i>Ex.:</b></i> Aluguel lançado no ano de 2021 em 12 parcelas, é possível lançar essa despesa para o ano de 2022.

Exemplificando um fornecedor lançado no ano de 2021.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_1.PNG" />
<br></br>

Para gerar a despesa recorrente, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_pesquisar.PNG" />, depois em <i>(Adicionar/Remover filtro)</i> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_filtro.PNG" /> para buscar a despesa.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_2.PNG" />
<br></br>

Selecione o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_Botao_gerar.PNG" /> para gerar a despesa recorrente.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Despesas_recorrentes_vencimentos.png" />
<br></br>

Processo finalizado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Despesas_recorrentes_lan%C3%A7adas.PNG" />
<br></br>

Pode-se verificar o lançamento da despesa recorrente pelo <i>(Menu > Financeiro > Contas a pagar).</i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_3.PNG" />
<br></br>


<div id="formasdepagamentos" />
<b>16. Formas de pagamentos</b>
<br></br>

Formas de pagamentos <i>(Menu > Financeiro > Formas de pagamentos)</i>, possível cadastrar as formas de pagamentos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/17_Formas_pagamentos_2.PNG" />
<br></br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Ordem:** Ordem que vai aparecer na tela de pagamentos, em recibos quando for selecionar a forma de pagamento, veja que a forma de pagamento dinheiro é a primeira a ser apresentada, pois a mesma esta com a Ordem 1 conforme imagem anterior.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/17_Formas_pagamentos_3.PNG" />
<br></br>

**c. Descrição:** Descrição do formato do pagamento. <i><b>Ex.:</b> Dinheiro, cheque, cartão,pix,transferência,etc.</i>

**d. Conta padrão:** Conta que será creditada. <i><b>Ex.:</b> Caixa do cartório, Itaú,Sicoob,etc.</i>

**e. Liquidação:**  Selecione entre as 4 opções <i>(Automática, Manual, Programada d+, Programada fixa)</i>. 
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Automatica.PNG" /> Quando a forma de pagamento for dinheiro, cai automaticamente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Manual.PNG" /> Forma de pagamento cheque ou boleto, é necessário consultar o extrato bancário para validar se o dinheiro já se encontra na conta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_ProgramadaD%2B.PNG" /> Data que será creditado na conta do cartório. <i><b>Ex.:</b> Cartão de débito, usando d+1 o pagamento cairia no dia + 1</i>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_ProgramadaFixa.PNG" /> Data fixa para ser creditada na conta do cartório. <i><b>Ex.:</b> Cartão de crédito, dia fixo pro pagamento cair na conta.</i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Taxa.PNG" /> Taxa administrativa, utilizada quando houver necessidade.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_N%C3%A3o_Acrescentar.PNG" /> Selecionar de acordo com a forma que trabalha o cartão <i><b>Ex.:</b> Cartexpress,etc.</b></i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Permitir_Parcelamento.PNG" /> Segue a mesma funcionalidade do item anterior.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Realizar_analise.PNG" /> Refere-se ao item [1. Análise de crédito ](#analise).

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Desativada.PNG" /> Desativa a forma de pagamento.
<br></br>


<div id="logsfinanceiros" />
<b>17. Logs financeiros</b>
<br></br>

Logs financeiros <i>(Menu > Financeiro > Logs financeiros)</i>  são registros de eventos ocorridos dentro do <i>Menu financeiro</i>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_1.PNG" />
<br></br>

Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Logs_Financeiros_botao_pesquisar.PNG" /> será apresentado todos os logs financeiros do cartório.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_2.PNG" />
<br></br>

Para realizar o filtro de um log especifico, preencha o campo com o filtro que necessita realizar a pesquisa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_3.png" />
<br></br>

Selecionando a forma de pesquisa, o sistema retornará da seguinte maneira:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_4.PNG" />
<br></br>

 
<div id="pastas" />
<b>18. Pastas</b>
<br></br>

Pastas <i>(Menu > Financeiro > Pastas)</i> , tem a funcionalidade de organizar em qual pasta a conta se encontra. ***Ex.:** Mensalistas com dívidas, mas não vão efetuar o pagamento, por exemplo, podem ser inseridos na pasta **"inadimplentes"***.

Clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> para criar a pasta.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_2.PNG" />
<br></br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Descrição:** Nome da pasta que será criada.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_criacao_Arquivar_titulos_desta_pasta.PNG" /> Ao marcar o CHECKBOX os títulos serão arquivados, não mais apresentados em telas como contas a receber, por exemplo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_criacao_desativar.PNG" /> A pasta será desativada.

Ao criar a pasta,  a mesma será apresentada da seguinte maneira:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_3.PNG" />

Para utilizar esta pasta, basta acessar o <i>(Menu > Financeiro > Contas a receber).</i>

Pesquise o mensalista que precisa ser arquivado na pasta inadimplentes pelo binóculo <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Devedor.PNG" />.
<br></br>

Neste exemplo vamos filtrar o <i>mensalista teste:</i>

Selecione os títulos que devem ser arquivados na pasta e clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Contas_Receber_Botao_Abrir.PNG" />, será apresentado a seguinte tela:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_5.PNG" />
<br></br>

Basta selecionar a pasta criada <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pasta_selecionando_pasta.png" />.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_6.PNG" />
<br></br>


Após preencher o campo pasta, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Contas_a_receber_Botao_Salvar.PNG" />
para que o título seja salvo na pasta inadimplentes. Note que depois de salvo, o título não aparecerá mais na tela de contas as receber conforme imagem abaixo:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_7.PNG" />
<br></br>


Também é possível pesquisar o título que foi arquivado na pasta inadimplentes, acessando o (*Menu > Financeiro > Contas a receber*), pesquise pelo nome do cliente para que possa aparecer o título arquivado como inadimplentes.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_8.PNG" />
<br></br>


<div id="planodecontas" />
<b>19. Plano de contas</b>
<br></br>


Plano de contas <i>(Menu > Financeiro > Plano de contas)</i> é possível cadastrar as contas de receitas e despesas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Plano_Contas.PNG" />
 <br></br>


Para criar um novo plano de contas, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Novo.PNG" /> depois em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Botao_novo.PNG" /> neste exemplo criaremos o plano de conta <i>Receitas</i>. 
<br></br>


<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_2.PNG" />
<br></br>

A seguir, será demonstrado o plano de contas com suas subcontas.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_3.PNG" />
<br></br>

Para criar uma subconta, selecione a conta pela qual será criada a subconta <b>ex.:</b> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Despesas.PNG" /> em seguida em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> .
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_4.PNG" />
<br></br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Conta:** Ordem que a conta será apresentada no plano de contas.

**c. Carnê leão:** Número da conta do carnê leão.

**d. Descrição:** Descrição da conta, <i><b>ex.:</b> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Plano_contas_botao_aluguel.PNG" /></i>.


**e. Conta superior:** Conta superior da conta criada, <i><b>ex.:</b> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Despesas.PNG" /></i>.

**f. Previsão mensal:** Valor previsto mensalmente para entrar/sair do plano de contas.

**g. Marcação:** Recurso para filtrar a conta com um código interno, podendo utilizar esse filtro na emissão do relatório livro caixa <i>(Menu > Financeiro > Relatórios > R. Livro caixa)</i>.

**h. Observações:** Pode-se colocar observações referente ao plano de contas criado.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Conta_de_resultados.PNG" /> Apura resultado financeiro, se desmarcar não será apresentado no relatório de livro caixa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Contas_receber.PNG" /> Deve-se marcar quando se tratar de contas a receber <i>ex.: <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Plano_contas_botao_receitas.PNG" /></i>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_A_Pagar.PNG" /> Marcar quando se referir a contas a pagar
<i><b>ex.:</b> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Despesas.PNG" /></i>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_N%C3%A3o_dedutivel.PNG" /> Com esta opção marcada o plano de conta não gera imposto de renda.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Recorrente.PNG" /> Quando se tratar de despesas recorrente, marque essa opção. <i><b>ex.:</b> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Plano_contas_botao_aluguel.PNG" /></i>..

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Desativo.PNG" /> Desativa o plano de contas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Transferir_Conta.PNG" /> <i>Transferir conta:</i> Possível transferir uma conta para dentro de outra ou transferir para fora.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_5.PNG" />
<br></br>

Neste exemplo, foi criado a conta de aluguel como receita, mas se trata de uma despesa, basta clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Transferir_Conta.PNG" /> para transferir a conta.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_6.PNG" />
<br></br>
Subconta se encontra no plano de contas receitas com número <b>2.2</b>. Aluguel, a mesma será transferida para o plano de contas despesas número <b>2</b>.
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_7.PNG" />
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_8.PNG" />
<br></br>

Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_sim.PNG" /> a subconta será transferida.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_9.PNG" /> 
<br></br>


<div id="receitasfixas" />
<b>20. Receitas fixas</b>
<br></br>


Receitas fixas <i>(Menu > Financeiro > Receitas fixas)</i>, é possível cadastrar uma receita fixa do cartório.  <b>Ex.:</b> O cartório vai receber determinado valor em dez vezes. As dez parcelas vão para o contas a receber.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_1.PNG" />
<br></br>

**a. Devedor:** Devedor do título a receber.

**b. Plano de contas:** Plano de contas que será creditado o título.

**c. Histórico:** Histórico referente a receita lançada.

**d. Complemento:** A forma que será lançado as parcelas. <i><b>Ex.:</b> Mês/Ano, Parcela.</i> 

**e. Documento:** Para colocar o número do documento se o cartório trabalhar com essa opção.

**f. Qtde. parcelas:** Informe o número total de parcelas a ser parceladas para o recebimento do título.

**g. Valor parcela:** Valor a ser cobrado por cada parcela.

**h. Total:** Valor total do parcelamento.
<br></br>

Preencha as informações conforme os passos passados:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_2.PNG" />
<br></br>

Após preencher, basta selecionar o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" /> para gerar a receita fixa.

Será apresentado a seguinte tela:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_3.PNG" />
<br></br>

As parcelas foram geradas, mas para finalizar o processo, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" />.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_4.PNG" />
<br></br>

Para conferência das receitas fixas lançadas, acesse o <i>(Menu > Financeiro > Contas a receber)</i>, pesquise pelo nome do devedor como imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_5.PNG" />
<br></br>


<div id="remessadeboleto" />
<b>21. Remessa de boletos</b>
<br></br>

Remessa de boletos <i>(Menu > Financeiro > Remessa de boletos)</i> , utilizada para gerar arquivo de remessa ao banco, para que o banco tenha conhecimento da cobrança registrada. 
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/22_Remessa_Boletos_1.PNG" />
<br></br>

**Tipo:** Selecione entre os 2 tipos <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Remessa_Boleto_Tipo.png" /> .

**Dt. emissão:** Data automática do dia da  emissão, mas poderá ser alterada.  

**Dt. remessa:** Deve ser usado para gerar novamente arquivos já remetidos ao banco.

**Dt. inicial:** Data automática do dia, mas poderá ser alterada caso necessário.

**Dt. final:** Data automática do dia, mas poderá ser alterada caso necessário.

**Conta:** Conta bancária que será creditado o boleto.

**Layout:** Layout de informações entre bancos e empresas.

**Tabela de títulos:** Apresenta todos os boletos gerados para a conta seleciona.
<br></br>

Após realizar o preenchimento dos campos, basta clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Remessa_Boleto_Botao_Gerar.PNG" />, será gerado um arquivo em txt ,pelo qual será usado para importar dentro do sistema do banco, nesse exemplo utilizamos a conta Sicoob.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/22_Remessa_Boletos_2.PNG" />  
<br></br>

Esse arquivo será salvo na pasta conforme imagem a seguir:
<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Remessa_Boleto_Salva.PNG" />
<br></br>

*Obs:* Esse caminho é salvo quando realizamos as configurações das contas financeiras para emissão de boleto autorizada pelo <i>(Menu > Financeiro > Contas Financeiras)</i>.

<div id="retornodeboleto" />
<b>22. Retorno de boletos</b>
<br></br>

Retorno de boletos <i>(Menu > Financeiro > Retorno de boletos)</i> Utilizado para fazer download dos boletos pagos no dia anterior no banco para importar e dar baixa no Acsiv.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Retorno_Boletos.PNG" />
<br></br>

Como estamos em uma base de homologação não será possível apresentar a tela com os devidos títulos<i>(boletos)</i> , mas ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Retorno_Boletos_Importar.PNG" /> é possível pegar os títulos<i>(boletos)</i> que foram exportados do sistema do banco para serem importados dentro do Acsiv. Ao finalizar a importação, basta clicar no botão confirmar para finalizar o processo de retorno de boletos dentro do Acsiv. 
<br></br>

<div id="tabelair" />
<b>23. Tabela IR</b>   
<br></br>

Tabela IR <i>(Menu > Financeiro > Tabela IR)</i>.

**IMPOSTO DE RENDA (IR)**

É por meio dessa tabela que o sistema consegue calcular a porcentagem para gerar o imposto de renda. 

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/TabelaIR.PNG" />
 </div>

**a. Ano:** Selecione o ano para gerar a tabela IR.

**b. Tipo:** Pessoa Física (PF) ou Pessoa Jurídica (PJ).



Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Tabela_Gerar.PNG" /> é possível visualizar.
<br></br>

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/TabelaIR_Gerada.PNG" />
</div>
<br></br>

<div id="transferências" />
<b>24. Transferências</b> 
<br></br>

Transferências <i>(Menu > Financeiro > Transferências)</i>, utilizado para realizar transferências entre contas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/24_Transferencias_1.PNG" />
<br></br>

Preencha os campos para a realização da transferência, nesse exemplo foi transferido um valor do <i>CAIXA</i> (caixa físico do cartório) para a conta bancária <i>SICOOB</i>nta bancário do cartório).

Após o preenchimento dos campos, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Transferir_Bot%C3%A3o.PNG" /> para efetivar a transferência entre as contas.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/24_Transferencias_2.PNG" />
<br></br>

Logo, a transferência será registrada no Contas a pagar / Contas a receber, <i>(Menu > Financeiro > contas a pagar / contas a receber).</i>
<br></br>


<i>Contas a pagar:</i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/24_Transferencias_3.PNG" />

<i>Contas a receber:</i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/24_Transferencias_4.PNG" />

**OBS:** Vale lembrar que essa transferência acontece apenas dentro do cartório pelas contas cadastradas no  no <i>(Menu > Financeiro > Contas financeiras)</i> não movimenta a conta bancária real do cartório <i>(Controle interno)</i>.
<br></br>


<div id="relatórios" />
<b>25. Relatórios</b> 
<br></br>
Os Relatórios concentram um conjunto de informações com o objetivo de reportar resultados parciais ou totais de uma determinada prática do cartório.

<div align="center">
 Para acessar um relatório (<i>Menu > Financeiro > Relatórios</i>)<br></br>
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_1.png" width="450" />
</div>
<br>

Vale lembrar, que existe a possibilidade de realizar filtros na emissão do relatório, com base no relatório de <i>contas a pagar</i> , segue exemplo: 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_2.PNG" />

Demonstraremos como inserir filtros nos relatórios:

* **Credores:** É possível colocar o credor para realizar o filtro.

  Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Inserir_linha_filtro_relatorio.PNG" /> há a possibilidade de buscar no cadastro do sistema o credor para realizar o filtro.

* **Plano de contas:** Selecione o plano de contas que será utilizado no filtro.

* **Contas financeiras:** Possível escolher a conta financeira para colocar no filtro.

* **Pastas:** Selecione a pasta que deseja trazer no filtro do relatório.

* **Centro de custos:** É possível selecionar um centro de custo no filtro do relatório.

* **Grupos econômicos:**  Possibilidade de colocar grupo econômico no filtro.
<br></br>

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/ConsolidarCartorios.PNG" /> Utilizado para o cartório que tem mais de um cartório em um banco.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_Pagar_Curva.PNG" /> Aplica a curva de experiência ABC, também chamada de análise de Pareto ou regra 80/20.
  <br></br>

  Ao selecionar o checkbox <i>aplicar curva abc</i> será apresentado a porcentagem <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_A_Pagar_Porcentagem_Curva.PNG" />. 


  Ao selecionar o período desejado, basta clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_A_Pagar_Bot%C3%A3o_Visualizar.PNG" />  para emissão do relatório conforme imagem a seguir:
  <br></br>

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_3.PNG" />

  <br></br>

  <div align="center"><i>Botões:</i></div> 
  <br></br>

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_visualizar.PNG" /> Ao realizar os filtros necessários, clique em visualizar para ter acesso ao relatório.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_imprimir.PNG" /> Direciona o relatório para sua impressora.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_fecha.PNG" /> Fecha a tela.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_pdf.PNG" /> Exporta o relatório em arquivo pdf.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_xls.PNG" /> Exporta o relatório em arquivo xls. 

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_email.PNG" /> Possibilidade de enviar o arquivo via e-mail, selecionando uma das opções <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_email_opcoes.png" />.

  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_checkbox_separador_linhas.PNG" /> Tem a funcionalidade de organizar a visualização do relatório.  
  <br></br>
   
<div id="rboletos" />
<b>R. Boletos</b> 
<br></br>

<div align="center"><i>Relatório Boletos:</i></div>  
<br></br>
Relatório de boletos retorna todos os boletos gerados dentro do sistema.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_4.PNG" />
<br></br>

**a. Data:** Selecione entre as 3  opções para visualização <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Boletos_Datas.png" />.

**b. Dt. inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário. 

**c. Dt. final:** Data final automática do dia, mas poderá ser alterada. 

**d. Conta:** É possível selecionar a conta pela qual será emitida o relatório.
<br></br>

<div id="rcontasapagar" />
<b>R. Contas a pagar</b> 
<br></br>

<div align="center"><i>Relatório Contas a pagar:</i></div>  
<br></br>

No relatório de contas a pagar, é possível identificar o lançamento de todas as contas a pagar do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_5.PNG" />
<br></br>

**a. Situação:** Poderá selecionar entre as 4 situações  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_Pagar_Situacao.png" />.

**b. Data:**  Possível selecionar entre as 3 datas  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_Pagar_Data.png" />.

**c. Dt. inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário.

**d. Dt. final:** Data final automática do dia, mas poderá ser alterada caso necessário.

**e. Relatório:** Pode-se filtrar entre as 4 opções  <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_Pagar_Relatorio.png" />. 

**f. Tipo:** Possibilidade de emissão por <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Contas_Pagar_Tipo.PNG" />. 
<br></br>
     
<div id="rcontasareceber" />
<b>R. Contas a receber</b>
<br></br>
<div align="center"><i>Relatório Contas a receber:</i></div>  
<br></br>

Relatório de contas a receber, são concentrados todas as contas a receber do cartório.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_6.PNG" /> 
<br></br>

Os campos tem as mesmas funcionalidades do relatório de contas a pagar, o que difere, que agora se trata do relatório de contas a receber.
<br></br>

<div id="rextratodecontas" />
<b>R. Extrato de contas</b>
<div align="center"><i>Relatório Extrato de contas:</i></div>  
<br></br>


Possível visualizar registros de contas financeiras do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_7.PNG" /> 
<br></br>

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:** Data final do dia, mas poderá ser alterada.

**c. Situação:** Selecione entre as 3 situações ( Realizados, Previstos, Todos).

**d. Tipo:** Selecione entre os 2 tipos (Resumido ou Detalhado).

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Extrato_Contas_Exibir_Saldo.PNG" /> Exibe o saldo da conta.
<br></br>

<i>Para filtrar uma determinada conta financeira, basta inserir os dados nas abas contas financeiras e formas de pagamento conforme exemplo abaixo:</i>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Extrato_contas_Filtro_Contas_financeiras.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Extrato_Contas_Filtro_Formas_Pagamento.PNG" />
<br></br>

<div id="rextratodemensalistas" />
<b>R. Extrato de mensalistas</b>
<div align="center"><i>Relatório Extrato de mensalistas:</i></div>  
<br></br>

Possível visualizar os registros dos mensalistas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_8.PNG" />
<br></br>

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:**  Data final do dia, mas poderá ser alterada.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Extrato_Mensalistas_Nao_Exibir_Mensalistas_Com_Credito.PNG" /> Não exibe no relatório os mensalistas com crédito.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Extrato_Mensalistas_Nao_Exibir_Saldo_Anterior.PNG" /> Não exibe o saldo anterior dos mensalistas no relatório.
<br></br>

Na aba <i>Clientes (Mensalistas)</i>  é possível filtrar por um determinado cliente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_9.PNG" /> 
<br></br>

<div id="rfechamentodecaixa" />
<b>R. Fechamento de caixa</b>
<br></br>
<div align="center"><i>Relatório Fechamento de caixa:</i></div>  
<br></br>


O fechamento de caixa consiste no retorno do processo diário de conferência das entradas e saídas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_10.PNG" />  
<br></br>

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:** Data final do dia, mas poderá ser alterada.

**c. Relatório:** Selecione entre as 3 formas para apresentação <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Relatorio.png" />.

**d. Atendente:** Emitir o relatório por um atendente em específico. <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Atendente.png" />

**e. Origem:** Selecione entre as 2 origem, se foi praticado pelo caixa ou pelo balcão de notas <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Origem.png" />. 

**f. Forma PG:** Há a possibilidade de filtrar uma forma de pagamento para ser apresentado no relatório <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Forma_De_Pagamento.png" /> .
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Exibir_saldo.PNG" /> Exibe o saldo anterior do caixa. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_Caixa_exibir_saldo_marcado.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Agrupar_funcionario.PNG" /> Agrupa os atos por funcionário.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_caixa_agrupar_func_emissao.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Agrupar_plano_contas.PNG" /> Agrupa o plano de contas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_caixa_agrupar_plano_contas.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Exibir_taxas.PNG" />  Exibe a taxa do cartão como uma saída no relatório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_caixa_taxa_cartao.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Exibir_caixa_entrada.PNG" /> Apresentadas apenas as contas "Caixa" entradas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Exibir_caixa_saida.PNG" /> Retorna as contas "Caixas" para saídas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_Exibir_contas_resultado.PNG" /> Exibe as contas de resultado definidas no plano de contas como conta de resultado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_com_credito_mensalista.PNG" /> Pagamentos com créditos de mensalista serão apresentados.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_De_caixa_exibir_troco.PNG" /> Exibe troco devolvido ao cliente como uma saída no relatório. <i><b>Ex.:</b> Valor total do recibo  58.83, valor recebido 60.00, troco 1.17 devolvido ao cliente</i>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_caixa_exibir_troco_saida_emiss%C3%A3o.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Fechamento_caixa_exibir_troco_entrada.PNG" /> Exibe troco como entrada.
<br></br>

<div id="rlivroauxiliar" />
<b>R. Livro auxiliar</b>
<br></br>
<div align="center"><i>Relatório Livro auxiliar:</i></div>  
<br></br>


Segundo a corregedoria do CNJ <i>(Conselho Nacional de Justiça)</i>, a escrituração do livro auxiliar se trata da receita e da despesa pelos responsáveis pelas delegações do serviço extrajudicial de notas e de registro. 

Diante disso, o relatório livro auxiliar tem a finalidade de apresentar as receitas e despesas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_11.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_botao_termo_abertura.PNG" /> Termo de abertura  utilizado para assinatura digital do livro, se configurado pelo *(Menu > Cartório > Configurações > Aba Livros)*  é possível  criar um texto pre definido *(Texto criado conforme a necessidade do cartório)* , podendo criar o texto no termo de  abertura quanto no termo de encerramento conforme imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Botao_termo_abertura_Configuracao.PNG" />
<br></br>
   

**a. Data do lançamento:** Data do dia do lançamento da despesa/receita <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/r.Livro_Auxiliar_Data_lancamento.PNG" />.

**b. Tipo:** Selecione entre os 4 tipos <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Tipo.PNG" /> de acordo com a necessidade.

**c. Apuração:** Selecione a apuração correspondente <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Apuracao.PNG" />.

**d. Complemento:** Complemento para colocar no livro auxiliar conforme provimento nº 45/2015. Nele é possível colocar o número do livro, folha inicial, folha final para controle interno <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Complemento.PNG" />. 
<br></br>

**Mais opções:**

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Exibir_Emolumentos.PNG" /> Exibe os emolumentos líquidos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Agrupar.PNG" /> Agrupa os códigos dos atos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Agrupar_Servicos.PNG" /> Agrupa atos que tenha o mesmo código de tabela. *Ex.: Código da tabela 1401 Declaratória e 1401 Emancipação.*

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Impressao_sequencial.PNG" /> Exibe impressão sequencial dos atos pela data da pratica.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Exibir_Plano_Contas_Despesas.PNG" /> Exibe o plano de contas nas despesas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Nao_Exibir_Ato_Especial.PNG" /> O ato especial não será apresentado no relatório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Nao_Exibir_Quantidade.PNG" /> Não exibe a quantidade de atos realizados.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Acrescentar_Valor_Selo.PNG" /> Acrescenta o valor do selo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Exibir_Total_Por_Atribuicao.PNG" /> Exibe o total por atribuição.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Exibir_Descricao_Tabela.PNG" /> Exibe a descrição da tabela de emolumentos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Atos_Gratuitos.PNG" /> Exibe os atos gratuitos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Termo_Abertura_Encerramento.PNG" /> Exibe o termo de abertura e encerramento.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Selecionar_Atos.PNG" /> Seleciona os atos específicos para ser apresentados no relatório.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/R_Livro_Auxiliar_Selecionar_Atos.PNG" />
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/R_Livro_Auxiliar_Selecionar_Atos_Emissao.PNG" />
<br></br>

<div id="rlivrocaixa" />
<b>R. Livro caixa</b>
<br></br>
<div align="center"><i>Relatório Livro caixa:</i></div>  
<br></br>


Relatório de livro caixa tem a finalidade de apresentar os rendimentos oriundos dos serviços notariais e cartoriais que serão tributados mensalmente pelo imposto de renda pessoa física<i>(IRPF)</i>.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_14.PNG" />
<br></br>

 <i>Gerar Documentos</i> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Carne_Leao_Opcoes.png" /> é possível gerar guia DARF/Exportar Carnê Leão.
 <br></br>

**a. Data inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário. 

**b. Data final:** Data final automática do dia, mas poderá ser alterada caso necessário.

**c. Marcação PC:** Quando criado o plano de contas <i>(PC)</i> pelo <i>(Menu > Financeiro > Plano de contas)</i>, com o campo <i>Marcação PC</i> preenchido, é possível filtrar essa marcação para ser apresentada no relatório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Agrupar_Plano_Contas.PNG" /> Agrupa plano de contas  na apresentação do relatório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Detalhar_receitas_codigo_tabela.PNG" /> Detalha as receitas por código da tabela.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Detalhar_receitas_codigo_recibo.PNG" /> Detalha as receitas por código do recibo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Auxiliar_Nao_Exibir_Ato_Especial.PNG" /> O ato especial não será apresentado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_N%C3%A3o_Exibir_Lancamentos_nao_dedutiveis.PNG" /> Não será apresentado lançamentos que foi definido no plano de contas <i>(Menu > Financeiro > Plano de contas)</i>  como "Não dedutíveis".

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Exibir_Somente_Contas_Resultado.PNG" /> Exibe apenas contas que foram definidas como contas de resultado no plano de contas.  

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Exibir_deposito_previo.PNG" /> Exibe atos lançados no recibo <i>(Menu > Cartório > Recibos)</i> como depósito prévio.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Livro_Caixa_Exibir_Emolumentos_liquidos.PNG" /> Exibe emolumentos líquidos.
<br></br>
   
<div id="rplanodecontas" />
<b>R. Plano de contas</b>
<br></br>
<div align="center"><i>Relatório Plano de contas:</i></div>  
<br></br>

Relatório plano de contas, retorna todos os lançamentos praticados no cartório que foram definidos no  plano de contas <i>(Menu > Financeiro > Plano de contas).</i>

 <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_15.PNG" />
 <br></br>

**a. Data:** Selecione entre as 4 datas (Lançamento, vencimento, pagamento, liquidação).

**b. Dt. inicial:** Data inicial do dia, mas poderá ser alterada se necessário.

**c. Dt. final:** Data final do dia, mas poderá ser alterada se necessário.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Plano_Contas_Aplicar_Somatorio.PNG" /> Aplica somatório no início de cada grupo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Plano_Contas_Exibir_Somente.PNG" /> Exibe somente contas que foram marcadas como contas de resultados na criação do plano de contas <i>(Menu > Financeiro > Plano de contas).</i>
<br></br>

<i>Para visualizar apenas um plano de contas em específico, basta inserir o mesmo conforme imagem a seguir:</i> 
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Plano_Contas_Filtro.PNG" />
<br></br>

Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Plano_Contas_Botao_Visualizar.PNG" /> será exibido o relatório como abaixo:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Plano_Contas_Visualiza%C3%A7%C3%A3o.PNG" />
<br></br>

<div id="rreceitadiária" />
<b>R. Receita diária</b>
<div align="center"><i>Relatório Receita diária:</i></div>  
<br></br>

Relatório Receita diário exibe as receitas diárias do cartório.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/25_Relatorios_16.PNG" />
<br></br>

**a. Data inicial:** Data inicial do dia, mas poderá ser alterada se necessário.

**b. Data final:** Data final do dia, mas poderá ser alterada se necessário.

**c. Tipo:** Selecione entre os 4 tipos ( Resumido 1, Resumido 2, Detalhado 1, Detalhado 2).

**d. Ordem:** Selecione entre as 2 ordens ( Cód. tabela, Código).

**e. Atendente:** Será possível selecionar por um funcionário em específico.

**f. Origem:** Origem que foi realizado o ato, se foi praticado pelo caixa ou pelo balcão de notas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Exibir_Deposito_Previo_Convertido.PNG" /> Exibe depósito prévio convertido. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Nao_Agrupar_Por_Atendente.PNG" /> Não agrupa por atendente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Exibir_Recibos_Mensalistas.PNG" /> Exibe recibos de mensalistas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Exibir_Saidas_Caixa.PNG" /> Exibe saídas de caixa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Nao_Exibir_Deposito_Previo.PNG" /> Não exibe depósito prévio.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_Exibir_Adiantamentos_Processos.PNG" /> Exibe adiantamentos de processos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Exibir_Pagamentos_Mensalistas.PNG" /> Exibe pagamentos de mensalistas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_Nao_Exibir_Ato_Especial.PNG" /> Não exibe ato especial.
<br></br>

**Observações:** Ao preencher será exibida no relatório.
<br></br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_CB_Observacao.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/R.Receita_Diaria_Relatorio.PNG" />



















 





















 
