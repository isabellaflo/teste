<b>ÍNDICE:</b>

[1. ANÁLISE DE CRÉDITO](#analise)<br>
[2. BANCOS](#bancos)<br>
[3. BOLETOS](#boletos)<br>
[4. CAIXA - ENTRADAS](#caixaentradas)<br>
[5. CAIXA SAÍDAS](#caixasaídas)<br>
[6. CENTRO DE CUSTOS](#centrodecustos)<br>
[7. CONDIÇÕES DE PAGAMENTOS](#condiçõesdepagamentos)<br>
[8. CONTAS A PAGAR](#contasapagar)<br>
[9. CONTAS A RECEBER](#contasareceber)<br>
[10. CONTAS FINANCEIRAS](#contasfinanceiras)<br>
[11. CRÉDITO COMERCIAL](#créditocomercial)<br>
[12. DARF](#darf)<br>
[13. DESPESAS FIXAS](#despesasfixas)<br>
[14. DESPESAS RECORRENTES](#despesasrecorrentes)<br>
[15. FORMAS DE PAGAMENTOS](#formasdepagamentos)<br>
[16. LOGS FINANCEIROS](#logsfinanceiros)<br>
[17. PASTAS](#pastas)<br>
[18. PLANO DE CONTAS](#planodecontas)<br>
[19. RECEITAS FIXAS](#receitasfixas)<br>
[20. REMESSA DE BOLETOS](#remessadeboleto)<br>
[21. RETORNO DE BOLETOS](#retornodeboleto)<br>
[22. TABELA IR](#tabelair)<br>
[23. TRANSFERÊNCIAS](#transferências)<br>
[24. RELATÓRIOS](#relatórios)<br>
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


<div id="analise" />
<b>1. Análise de crédito</b>

Análise de crédito *(Menu > Financeiro > Análise de crédito)* pode ser utilizada como uma análise de crédito dos mensalistas do cartório. Bastando cadastrar um limite de crédito e informar o nível de risco de habilitar crédito para determinado cliente.

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/2_Analise_De_Credito.PNG" width="700" />
</div>

**a. Cedente:** Funcionário que realizou a análise de crédito.

**b. Tomador:** Mensalista *(Cliente)* analisado.

**c.  Análise:**  Analisa a situação do mensalista *(Cliente)* antes de liberar o crédito.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/2_1.png" /> selecionar as consultas realizadas durante a análise do cliente *(Mensalista)*.

**d. Nível de risco:**  O nível de risco varia de 0 a 9, sendo 0 muito seguro habilitar crédito e 9 muito arriscado. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/2_2.png" /> Crédito habilitado do nível de risco, é possível habilitar o crédito.

**e. Limite de crédito:**  Valor a liberar de crédito ao mensalista *(Cliente)*.

**f. Limite parcela:**  Limite da parcela a liberar ao mensalista *(Cliente).*

**g. Observações:** É possível colocar alguma observação referente ao cliente (*Mensalista*).


<div id="bancos" />
<b>2. Bancos</b>

Bancos *(Menu > Financeiro > Bancos)* é possível cadastrar banco, inserindo informações de número, dígito verificador e nome do banco.
   
<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/3_Banco.PNG" width="700" />
</div>

**a. Número:**  Número do banco.

**b. Dígito verificador:**  Acrescentar o dígito verificador.

**c. Nome:** Nome do banco.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/3_1.png" /> É possível desativar o banco se necessário.


<div id="boletos" />
<b>3. Boletos</b>

Boletos *(Menu > Financeiro > Boletos)* utilizado quando o próprio cartório emite boletos. Ao salvar, o Acsiv cria um registro em contas a Receber.  

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


<div id="caixaentradas" />
<b>4. Caixa - Entradas </b>


 Caixa - Entradas (*Menu > Financeiro > Caixa > Entradas*) Utilizado para realizar os lançamentos das receitas do cartório. *Ex.: "Valores que entraram para o cartório".*  

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/5_Caixa_Entradas.PNG" width="700" />
</div>
<br>

**a. Dt. Vencimento:** Data vencimento do dia, mas poderá ser alterada caso necessário.

**b. Dt. entrada:** Data entrada do dia, mas poderá ser alterada caso necessário.

**c. Valor:** Valor a ser recebido.

**d. Documento:** Opcional, se o cartório trabalhar com número de documento, preenche o campo.

**e. Func. resp.:** Funcionário que esta realizando a entrada. 

**f. Devedor:** Nome do devedor da entrada.

**g. Plano de contas:** Selecione o plano de contas para o recebimento da entrada.

**h. Histórico:** Histórico conforme achar viável. Ex: Recebimentos diversos ref. mês 08/2021.

**i. Forma de pagto.:** Forma de pagamento escolhida para realizada da entrada.

**j. Conta:** Conta escolhida para receber o valor da entrada.

**l. Dt. liquidação:** Data liquidação do dia, mas poderá preencher com a data da liquidação da entrada. *Ex.: Entrada realizada via pix programado para o dia seguinte, a data de liquidação, será o dia que foi liquidado na conta do cartório.* 

**m. N°controle:** Possível colocar o número de controle, se o cartório trabalhar com ele.


<div id="caixasaídas" />
<b>5. Caixa - Saídas </b>

Caixa - Saídas (*Menu - Financeiro - Caixas - Saídas*) Utilizado para realizar todas as saídas (despesas) do cartório. *Ex.: "Valores que saíram do cartório".*  


<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/5_Caixa_Entradas.PNG" width="700" />
</div>
<br>

**a. Dt. vencimento:** Data vencimento do dia, mas poderá ser alterada caso necessário.

**b. saída:** Data saída do dia, mas poderá ser alterada caso necessário.

**c. Valor:** Valor da saída.

**d. Documento:** Opcional, se o cartório trabalhar com número de documento, preenche o campo.

**e. Func.resp.:** Selecione o funcionário responsável pelo registro da entrada no sistema.

**f. Credor:**  Possível colocar o credor da saída. 

**g. Plano contas:** É possível selecionar o plano de contas para registro da saída.

**h. Histórico:** Histórico referente a saída, *ex.:  Cemig ref. Mês 08/2021.* 

**i. Forma de pagto.:** Forma de pagamento que será realizada a saída.

**j. Conta:**  Conta que será realizado a saída.

**l. Dt. liquidação:**  Data liquidação do dia, mas poderá preencher com a data da liquidação da saída. *Ex.: E Saída realizada via Transferência bancária  programada para o dia seguinte, a data de liquidação, será o dia que foi liquidado na conta do cartório.* 

**m. N° controle:**  Possível colocar o número de controle, se o cartório trabalhar com ele.


<div id="centrodecustos" />
<b>6. Centro de custos</b>

É utilizado para cadastrar algum centro de custo. Ex.: cartório possui dois veículos, por exemplo, e quer ter um controle sobre gastos/rendimento desses dois veículos. Nesse caso, eles poderiam cadastrar centros de custos sendo as placas dos veículos, por exemplo. Podemos acessar essa tela no *Menu > Financeiro > Centro de custos*.



<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_1.PNG" width="700" />
</div>
<br>

É possível pesquisar, criar um novo, abrir um centro de custos.

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_2.PNG" width="700" />
</div>
<br>

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/7_Centro_Custo_3.PNG" width="700" />
</div>
<br>

**a. Código:** Gerado automaticamente pelo sistema.

**b. Conta:** Conta criada no centro de custos.

**c. Descrição:** Neste exemplo estamos usando a placa de um veículo como a descrição.

**d. Conta superior:** Conta superior criada no Centro de custos.

Para desativar a conta, basta clicar no botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/3_1.png" />.


<div id="condiçõesdepagamentos" />
<b>7. Condições de pagamentos</b>

Condições de pagamentos *(Menu > Financeiro > Condições de pagamentos)* Utilizado somente em caso de parcelamentos. 

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

**c. Descrição:** Descrição do parcelamento *Ex.:* CARTEXPRESS.

**d. Vencimentos:**  Utilizado para colocar a forma que o pagamento deverá ocorrer. *Ex.:* 30/60/90 ou 0/15/45 dias.

**e. Fórmula:** Selecione entre os 5 fórmulas *(Nenhuma, Juro simples, Juro composto, Taxa de acréscimo, Taxa de desconto).* 

**f. Porcentual%:**  Percentual da condição de pagamento ao mês.

**Parcela mínima:** Valor da parcela mínima da condição do parcelamento.

**Ajuste de data:**  Ajuste de data. *Ex.: 15 dias pra frente.* 


<div id="contasapagar" />
<b>8. Contas a pagar</b>

Contas a pagar *(Menu > Financeiro > Contas a pagar)*, será apresentado todas as contas a pagar do cartório.

É possível pesquisar os títulos por um credor em especifico ou apenas selecionar o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/pesquisar.PNG" /> para visualizar como exemplo a seguir:

<div align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_1.PNG" width="700" />
</div>
<br>

Vamos utilizar apenas dois credores para exemplificar.

Os títulos apresentados na tela na parte superior <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/N%C3%A3o_Quitados.PNG" /> significa que são títulos em abertos que não foram quitados ainda, após quitar, o mesmo aparecerá na parte inferior da tela <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Quitados.PNG" />. 

**a. Credor:** Credor da conta a pagar.

**b. Dt. vencimento:** Selecione entre as 5 datas *(Vencimento, pagamento, programação, liquidação).* 
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


Selecione o título que deseja quitar.
<p align="center">
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_2.PNG" />
</p>

Ao selecionar, será apresentado a seguinte tela:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_3.PNG" />

Assim que a conta for quitada, na tela de contas a pagar será apresentada da seguinte maneira:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_4.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/abrir.PNG" />  possível abrir a conta a pagar selecionada para ter acesso as informações.

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

* *Alterações de vencimentos:*  É possível alterar os vencimentos dos títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_7.PNG" />

* *Desmembrar*: É possível desmembrar o título. *obs.:* Para desmembrar o título além de selecionar a parcela, o credor precisa esta selecionado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_8.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_9.PNG" />

* *Estornar:* É possível estornar um título que foi quitado indevidamente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_10.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_11.PNG" />

* *Excluir títulos:* Possível excluir títulos lançados indevidamente. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_12.PNG" />

* *Liquidar:*  **Falta pegar informação com Alisson de como funciona**.

* *Programar:* É possível programar a data que será quitado o título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_13.PNG" />
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_15.PNG" />

* *Taxas:*  **Falta pegar informação com Alisson de como funciona**.

* *Unificar:* É possível unificar dois títulos para pagar de uma só vez. *Obs.:* Precisa selecionar o credor antes de unificar os títulos conforme exemplo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_16.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_17.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/9_Contas_A_Pagar_18.PNG" /><br>


<div id="contasareceber"/>
<b>9. Contas a receber</b>

Conseguimos localizar todas as contas a receber do cartório,  pelo *(Menu > Financeiro > Contas a receber).* 

A movimentação da tela conta a receber se dá através do lançamento do recibo com mensalista (*cliente*), mas podemos lançar o contas a receber direto nessa tela caso houver necessidade.



<p align="center"<i> Demonstraremos um recibo para mensalista do Cartório.</i></p>

---

Detalharemos uma conta a receber através de um recibo para mensalista, pelo *(Menu > Cartório > Recibos)* para criar um novo recibo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/10_Recibo.PNG" />

Na forma de pagamento escolhemos o mensalista.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/10_Recibo_1.PNG" />

Como ficará esse recibo no contas a receber:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_1.PNG" />

Os títulos apresentados na tela na parte superior <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/N%C3%A3o_Quitados.PNG" /> significa que são títulos em abertos que não foram quitados ainda, após quitar, o mesmo aparecerá na parte inferior da tela <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Quitados.PNG" />



<center><i>Mostraremos algumas funcionalidades:</i></center>

---



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/pesquisar.PNG" />Pesquisa todas contas a receber do cartório. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/quitar.PNG" /> É possível quitar um ou mais títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_2.PNG" />
Assim que a conta for quitada, na tela de contas a receber será apresentada da seguinte maneira:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_3.png" /><br>

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> Para criar um novo título direto do contas a receber.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/abrir.PNG" /> Possível abrir um título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_4.PNG" />


<p align="center">
<i>Botão</i> <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/14.png" width="50" />  <i>ferramentas (Atalho ALT + M), possui algumas funcionalidades, são elas:</i>     
</p>

---



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Ferramentas_Receber.png" />



* *Alteração de valores:*  Ao selecionar o título é possível alterar os valores.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_5.PNG" />

* *Alteração de vencimentos:* Altera a data de vencimento do título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_6.PNG" />

* *Boletos:* Para emissão de boletos pelo sistema. 

**OBS:** *Para emitir boletos pelo sistema, precisa verificar se o banco é homologado no sistema, se sim, entrar em contato com o gerente do banco informando que gostaria de emitir boletos de terceiros.* 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_7.PNG" />

* *Desmembrar:* Utilizado para desmembrar títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_8.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_9.PNG" />

* *Duplicatas:* É possível gerar duplicatas referente ao título selecionado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_10.PNG" />



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_11.PNG" />

* *Estornar:* Pode-se estornar um título quitado.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_12.PNG " />

* *Excluir títulos:* É Possível excluir títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_13.PNG" />

* *Liquidar:* Há possibilidade de liquidar um título após quitado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_14.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_15.PNG" />

* *Notas promissórias:* É possível emitir notas promissórias dos títulos.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Notas_Promissorias_Contas_receber.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Notas_Promissorias_Contas_receber_Editado.PNG" />

* *Programar:* O sistema permite programar a data do recebimento do título.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_16.PNG" />

Após programada a data, será apresentado na tela de contas a receber com a *Dt. Programação* preenchida.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_17.PNG" />

* *Recibos:* É Possível emitir um recibo do título que foi quitado.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Recibos_Contas_Receber.PNG" />



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Recibos_Contas_Receber_Emitido_Editado.PNG" />

* *Taxas:* É Possível configurar uma taxa caso seja necessário.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_18.PNG" />



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_19.PNG" />

* *Unificar:* É possível unificar títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_20.PNG" />

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/11_Contas_Receber_21.PNG" />


<div id="contasfinanceiras" />
<b>10. Contas financeiras</b>

Contas financeiras *(Menu > Financeiro > Contas financeiras)* , utilizado para realizar cadastro de alguma conta financeira,  se for o caixa físico do cartório, basta marcar tipo *Caixa* e colocar o nome desejado. Se for banco, deve-se preencher algumas outras informações, conforme imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/12_Contas_Financeiras_1.PNG" />

**a. Código:**  Gerado automaticamente pelo sistema.

**b.Cartório:** Utilizado para colocar nome do cartório.

**c.Tipo:** Selecione entre os 2 tipos *(Caixa, Bancária)* , *ex.: Caixa físico do cartório ou banco*.

 **d.Conta:**  Pode-se colocar a conta do banco.

**e. Banco:** É possível colocar o nome do banco.

**f. Agência:** Pode-se colocar a agência.

**g. Limite de crédito:** Utilizado somente para conhecimento do usuário, caso queira consultar.

<p align="center">
<i>CHECKBOXES da tela:</i>     
</p>

---



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_n%C3%A3o_fecha_caixa.PNG" /> Ao marcar essa opção, não será apresentado nenhum informação nos relatórios do financeiro.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_desativada.PNG" />Ao marcar, será desativado essa conta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/checkbox_emissao_de_boleto_autorizada.PNG" /> Quando o cartório trabalha com emissão de boletos, deve-se marcar o checkbox e preencher as informações conforme imagem abaixo. *OBS.: Essas informações são fornecidas pelo banco*. Mas se o cartório ainda não trabalha com emissão de boletos e gostaria de trabalhar. É necessário verificar se o banco é homologado,se sim, entrar em contato com o gerente, informar que quer emitir boleto de terceiros.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/12_Contas_Financeiras_2.PNG" />

**Aba Arquivos:** Só é preenchida depois que o aplicativo do banco estiver instalado na máquina.

**Aba Especial:** É preenchida quando a conta está em nome de pessoa jurídica, por exemplo, mas por alguma razão é necessário que o boleto saia no CPF.


<div id="créditocomercial" />
<b>11. Crédito comercial</b>

Crédito comercial *(Menu > Financeiro > Crédito comercial)*, funciona como uma espécie de pré-pago, o cliente "compra créditos" antes de precisar usar.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/13_Credito_Comercial_1.PNG" />

Ao selecionar o histórico de créditos <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Historico_creditos.PNG" /> é possível verificar todo o histórico de crédito do cliente.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/13_Credito_Comercial_2.PNG" />


<div id="darf" />
<b>12. DARF</b>

Darf *(Menu > Financeiro > DARF)* -  *Sigla para Documento de Arrecadação de Receitas Federais*, pode- se emitir guia pelo sistema.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_1.PNG" />

Basta preencher os dados para emissão da guia, conforme imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_2.PNG" />

Ao finalizar o preenchimento dos campos, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Bot%C3%A3o_Visualizar.PNG" /> para imprimir a guia DARF.



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/14_Darf_3.PNG" />


<div id="despesasfixas" />
<b>13. Despesas fixas</b>

Despesas fixas (*Menu > Financeiro > Despesas fixas*) *Ex.: Carnê de pagamento em 12 parcelas vão para o contas a pagar*.

Em seguida, será apresentada a tela para preenchimento das despesas fixas. 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_1.PNG" />

Com todas informações preenchidas, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" />.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_2.PNG" />

Agora, com as despesas fixas gerada será apresentada a seguinte tela:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_5.PNG" />

Clique novamente em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" /> para concluir a geração dos títulos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_6.PNG" />

Para encontrar o lançamento dessa despesa *(Menu > Financeiro > Contas a pagar)* ,pesquise pelo nome do credor para encontrar os títulos.
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/15_Despesas_fixas_7.PNG" />


<div id="despesasrecorrentes" />
<b>14. Despesas recorrentes</b>

Despesas recorrentes *(Menu > Financeiro > Despesas recorrentes)*, é um facilitador das despesas fixas anuais. *Ex.:* Aluguel lançado no ano de 2021 em 12 parcelas, é possível lançar essa despesa para o ano de 2022.

Exemplificando um fornecedor lançado no ano de 2021.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_1.PNG" />

Para gerar a despesa recorrente, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_pesquisar.PNG" />, depois em (*Adicionar/Remover filtro*) <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_filtro.PNG" /> para buscar a despesa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_2.PNG" />

Selecione o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Despesas_recorrentes_Botao_gerar.PNG" /> para gerar a despesa recorrente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Despesas_recorrentes_vencimentos.png" />

Processo finalizado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/Despesas_recorrentes_lan%C3%A7adas.PNG" />

Pode-se verificar o lançamento da despesa recorrente pelo *Menu > Financeiro > Contas a pagar.*

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/16_Despesas_recorrentes_3.PNG" />


<div id="formasdepagamentos" />
<b>15. Formas de pagamentos</b>

Formas de pagamentos *(Menu > Financeiro > Formas de pagamentos)*, possível cadastrar as formas de pagamentos.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/17_Formas_pagamentos_2.PNG" />

**a. Código:** Gerado automaticamente pelo sistema.

**b. Ordem:** Ordem que vai aparecer na tela de pagamentos, em recibos quando for selecionar a forma de pagamento, veja que a forma de pagamento dinheiro é a primeira a ser apresentada, pois a mesma esta com a Ordem 1 conforme imagem anterior.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/17_Formas_pagamentos_3.PNG" />

**c. Descrição:** Descrição do formato do pagamento. *Ex.: Dinheiro, cheque, cartão,pix,transferência,etc.*

**d. Conta padrão:** Conta que será creditada. *Ex. Caixa do cartório, Itaú,Sicoob,etc.*

**e. Liquidação:**  Selecione entre as 4 opções *(Automática, Manual, Programada d+, Programada fixa)*.  

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Automatica.PNG" /> Quando a forma de pagamento for dinheiro, cai automaticamente.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Manual.PNG" /> Forma de pagamento cheque ou boleto, é necessário consultar o extrato bancário para validar se o dinheiro já se encontra na conta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_ProgramadaD%2B.PNG" /> Data que será creditado na conta do cartório. *Ex.: Cartão de débito, usando d+1 o pagamento cairia no dia + 1*.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_ProgramadaFixa.PNG" /> Data fixa para ser creditada na conta do cartório. *Ex.: Cartão de crédito, dia fixo pro pagamento cair na conta.*
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Taxa.PNG" /> Taxa administrativa, utilizada quando houver necessidade.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_N%C3%A3o_Acrescentar.PNG" /> Selecionar de acordo com a forma que trabalha o cartão *Ex.: Cartexpress,etc.* 

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Permitir_Parcelamento.PNG" /> Segue a mesma funcionalidade do item anterior.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Realizar_analise.PNG" /> Refere-se ao item 1. Análise de crédito.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Formas_De_Pagamentos_Desativada.PNG" /> Desativa a forma de pagamento.


<div id="logsfinanceiros" />
<b>16. Logs financeiros</b>


Logs financeiros *(Menu > Financeiro > Logs financeiros)*  são registros de eventos ocorridos dentro do Menu financeiro.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_1.PNG" />

Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Logs_Financeiros_botao_pesquisar.PNG" /> será apresentado todos os logs financeiros do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_2.PNG" />

Para realizar o filtro de um log especifico, preencha o campo com o filtro que necessita realizar a pesquisa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_3.png" />

Selecionando a forma de pesquisa, o sistema retornará da seguinte maneira:
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/18_Logs_financeiros_4.PNG" />

 
<div id="pastas" />
<b>17. Pastas</b>

Pastas *(Menu > Financeiro > Pastas)* , tem a funcionalidade de organizar em qual pasta a conta se encontra. ***Ex.:** Mensalistas com dívidas, mas não vão efetuar o pagamento, por exemplo, podem ser inseridos na pasta **"inadimplentes"***.

Clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> para criar a pasta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_2.PNG" />

**a. Código:** Gerado automaticamente pelo sistema.

**b. Descrição:** Nome da pasta que será criada.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_criacao_Arquivar_titulos_desta_pasta.PNG" /> Ao marcar o CHECKBOX os títulos serão arquivados, não mais apresentados em telas como contas a receber, por exemplo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_criacao_desativar.PNG" /> A pasta será desativada.

Ao criar a pasta,  a mesma será apresentada da seguinte maneira:
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_3.PNG" />

Para utilizar esta pasta, basta acessar o (*Menu > Financeiro > Contas a receber*).

Pesquise o mensalista que precisa ser arquivado na pasta inadimplentes pelo binóculo <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Devedor.PNG" />.

Neste exemplo vamos filtrar o *mensalista teste:*
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Devedor.PNG" />

Selecione os títulos que devem ser arquivados na pasta e clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Contas_Receber_Botao_Abrir.PNG" />, será apresentado a seguinte tela:
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_5.PNG" />

Basta selecionar a pasta criada <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pasta_selecionando_pasta.png" />.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_6.PNG" />


Após preencher o campo pasta, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Pastas_Contas_a_receber_Botao_Salvar.PNG" />
para que o título seja salvo na pasta inadimplentes. Note que depois de salvo, o título não aparecerá mais na tela de contas as receber conforme imagem abaixo.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_7.PNG" />


Também é possível pesquisar o título que foi arquivado na pasta inadimplentes, acessando o (*Menu > Financeiro > Contas a receber*), e pesquise pelo nome do cliente para que possa aparecer o título arquivado como inadimplentes.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/19_Pastas_8.PNG" />

Como mostrado na imagem anterior, o título marcado como inadimplentes é a primeira linha.


<div id="planodecontas" />
<b>18. Plano de contas</b>


Plano de contas (*Menu > Financeiro > Plano de contas*) é possível cadastrar as contas de receitas e despesas do cartório.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_1.PNG" />



Para criar um novo plano de contas, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_2.PNG" />, depois em !<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Botao_novo.PNG" /> , neste exemplo criaremos o plano de conta *Receitas*. 



<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_2.PNG" />

A seguir, será demonstrado o plano de contas com suas subcontas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_3.PNG" />

Para criar uma subconta, selecione a conta pela qual será criada a subconta *ex.:* <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Despesas.PNG" />, em seguida em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Novo.PNG" /> .

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_4.PNG" />

**a. Código:** Gerado automaticamente pelo sistema.

**b. Conta:** Ordem que a conta será apresentada no plano de contas.

**c. Carnê leão:** Número da conta do carnê leão.

**d. Descrição:** Descrição da conta, *ex.: Aluguel*.

**e. Conta superior:** Conta superior da conta criada, *ex.: 2.Despesas*.

**f. Previsão mensal:** Valor previsto mensalmente para entrar/sair da conta.

**g. Marcação:** Recurso para filtrar a conta com um código interno, podendo utilizar esse filtro na emissão do relatório livro caixa *(Menu > Financeiro > Relatórios > R. Livro caixa)*.

**h. Observações:** Pode-se colocar observações referente ao plano de contas criado.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Conta_de_resultados.PNG" /> Apura resultado financeiro, se desmarcar não será apresentado no relatório de livro caixa.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Contas_receber.PNG" /> Deve-se marcar quando se tratar de contas a receber *Ex.:* <font color = 'green'> Receitas</font>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_A_Pagar.PNG" /> Marcar quando se referir a contas a pagar *Ex.:*  <font color = 'red'> Despesas</font>.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_N%C3%A3o_dedutivel.PNG" /> Com esta opção marcada o plano de conta não gera imposto de renda.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Recorrente.PNG" /> Quando se tratar de despesas recorrente, marque essa opção. *Ex.: Aluguel*.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_contas_Desativo.PNG" /> Desativa o plano de contas.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Transferir_Conta.PNG" /> *Transferir conta:* Possível transferir uma conta para dentro de outra ou transferir para fora.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_5.PNG" />

Neste exemplo, foi criado a conta de aluguel como receita, mas se trata de uma despesa, basta clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Transferir_Conta.PNG" /> para transferir a conta.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_6.PNG" />  Subconta se encontra no plano de contas receitas com número **1.2**. Aluguel, a mesma será transferida para o plano de contas despesas número **2**..
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_7.PNG" />
<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_8.PNG" />

Ao clicar em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_sim.PNG" /> a subconta será transferida.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/20_Plano_Contas_9.PNG" /> 

Perceba que a subconta ficou com o número **1.2**, basta clicar em cima da subconta <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Plano_Contas_Subconta_Aluguel.PNG" />  em seguida <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/abrir.PNG" />  para alterar para a numeração correta *ex.:*  **2.2**..

<img src="" />


<div id="receitasfixas" />
<b>19. Receitas fixas</b>


Receitas fixas *(Menu > Financeiro > Receitas fixas)*, é possível cadastrar uma receita fixa do cartório.  **Ex.:** O cartório vai receber determinado valor em dez vezes. As dez parcelas vão para o contas a receber.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_1.PNG" />

**a. Devedor:** Devedor do título a receber.

**b. Plano de contas:** Plano de contas que será creditado o título.

**c. Histórico:** Histórico referente a receita lançada.

**d. Complemento:** A forma que será lançado as parcelas. *Ex.: Mês/Ano, Parcela.* 

**e. Documento:** Para colocar o número do documento se o cartório trabalhar com essa opção.

**f. Qtde. parcelas:** Informe o número total de parcelas a ser parceladas para o recebimento do título.

**g. Valor parcela:** Valor a ser cobrado por cada parcela.

**h. Total:** Valor total do parcelamento.

Preencha as informações conforme os passos passados:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_2.PNG" />

Após preencher, basta selecionar o botão <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" /> para gerar a receita fixa.

Será apresentado a seguinte tela:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_3.PNG" />

As parcelas foram geradas, mas para finalizar o processo, clique em <img src="https://github.com/gislenetavaresacsiv/teste/blob/main/bot%C3%B5es/Botao_Gerar.PNG" />.

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_4.PNG" />

Para conferência das receitas fixas lançadas, acesse o (*Menu > Financeiro > Contas a receber*), pesquise pelo nome do devedor como imagem a seguir:

<img src="https://github.com/gislenetavaresacsiv/teste/blob/main/Novas_Imagens/21_Receitas_fixas_5.PNG" />


<div id="remessadeboleto" />
<b>20. Remessa de boletos</b>

Remessa de boletos *(Menu > Financeiro > Remessa de boletos)* , utilizada para gerar arquivo de remessa ao banco, para que o banco tenha conhecimento da cobrança registrada.  <img src="" />

**Tipo:** Selecione entre os 2 tipos <img src="" /> .

**Dt. emissão:** Data automática do dia da  emissão, mas poderá ser alterada.  

**Dt. remessa:** Deve ser usado para gerar novamente arquivos já remetidos ao banco.

**Dt. inicial:** Data automática do dia, mas poderá ser alterada caso necessário.

**Dt. final:** Data automática do dia, mas poderá ser alterada caso necessário.

**Conta:** Conta bancária que será creditado o boleto.

**Layout:** Layout de informações entre bancos e empresas.

**Tabela de títulos:** Apresenta todos os boletos gerados para a conta seleciona.

Após realizar o preenchimento dos campos, basta clicar em <img src="" />, será gerado um arquivo em txt ,pelo qual será usado para importar dentro do sistema do banco, nesse exemplo utilizamos a conta Sicoob.

<img src="" />  

Esse arquivo será salvo na pasta conforme imagem a seguir:
<img src="" />

*Obs:* Esse caminho é salvo quando realizamos as configurações das contas financeiras para emissão de boleto autorizada pelo *(Menu > Financeiro > Contas Financeiras)*.

<div id="retornodeboleto" />
<b>21. Retorno de boletos</b>

Retorno de boletos *(Menu > Financeiro > Retorno de boletos)* Utilizado para fazer download dos boletos pagos no dia anterior no banco para importar e dar baixa no Acsiv.

<img src="" />

Como estamos em uma base de homologação não será possível apresentar a tela com os devidos títulos*(boletos)* , mas ao clicar em <img src="" /> é possível pegar os títulos*(boletos)* que foram exportados do sistema do banco para serem importados dentro da Acsiv. Ao finalizar a importação, basta clicar no botão confirmar para finalizar o processo de retorno de boletos dentro do Acsiv. 

<div id="tabelair" />
<b>22. Tabela IR</b>   


Tabela IR *(Menu > Financeiro > Tabela IR)*.

**IMPOSTO DE RENDA (IR)**

É por meio dessa tabela que o sistema consegue calcular a porcentagem para gerar o imposto de renda. 

<img src="" />

**a. Ano:** Selecione o ano para gerar a tabela IR.

**b. Tipo:** Pessoa Física (PF) ou Pessoa Jurídica (PJ).



Ao clicar em <img src="" /> é possível visualizar.

<img src="" />


<div id="transferências" />
<b>23. Transferências</b> 

Transferências *(Menu > Financeiro > Transferências)*, utilizado para realizar transferências entre contas do cartório.

<img src="" />

Preencha os campos para a realização da transferência, nesse exemplo foi transferido um valor do *CAIXA* (caixa físico do cartório) para a conta bancária *ITAÚ* (conta bancário do cartório).

Após o preenchimento dos campos, clique em <img src="" /> para efetivar a transferência entre as contas.

<img src="" />

Logo, a transferência será registrada no Contas a pagar / Contas a receber, acesse o (*Menu > Financeiro > contas a pagar / contas a receber).*

*Contas a pagar:*

<img src="" />

*Contas a receber:* 

<img src="" />

**OBS:** Vale lembrar que essa transferência acontece apenas dentro do cartório pelas contas cadastradas no  no (*Menu > Financeiro > Contas financeiras*) não movimenta a conta bancária real do cartório (*Controle interno*).


<div id="relatórios" />
<b>24. Relatórios</b> 

Os Relatórios concentram um conjunto de informações com o objetivo de reportar resultados parciais ou totais de uma determinada prática do cartório.

<center>Para acessar um relatório (<i>Menu > Financeiro > Relatórios</i>).</center> 

​                                            ![1](C:\Users\Usuário\Desktop\BackupPC\Gislene\MANUAIS\Financeiro\1.png) 

 

Vale lembrar, que existe a possibilidade de realizar filtros na emissão do relatório. Com base no relatório de *contas a pagar* , segue exemplo: 

<img src="" />

Demonstraremos como inserir filtros nos relatórios:

* **Credores:** É possível colocar o credor para realizar o filtro.

  Ao clicar em <img src="" /> há a possibilidade de buscar no cadastro do sistema o credor para realizar o filtro.

* **Plano de contas:** Selecione o plano de contas que será utilizado no filtro.

* **Contas financeiras:** Possível escolher a conta financeira para colocar no filtro.

* **Pastas:** Selecione a pasta que deseja trazer no filtro do relatório.

* **Centro de custos:** É possível selecionar um centro de custo no filtro do relatório.

* **Grupos econômicos:**  Possibilidade de colocar grupo econômico no filtro.

  <img src="" /> Utilizado para o cartório que tem mais de um cartório em um banco.

  <img src="" /> Aplica a curva de experiência ABC, também chamada de análise de Pareto ou regra 80/20.

  Ao selecionar o checkbox *aplicar curva abc* será apresentado a porcentagem <img src="" />. 

  

  Ao selecionar o período desejado, basta clicar em <img src="" />  para emissão do relatório conforme imagem a seguir.

  <img src="" />

  

  <center><i>Botões:</i></center> 

  <img src="" /> Ao realizar os filtros necessários, clique em visualizar para ter acesso ao relatório.

  <img src="" /> Direciona o relatório para sua impressora.

 <img src="" /> Fecha a tela.

  <img src="" /> Exporta o relatório em arquivo pdf.

  <img src="" /> Exporta o relatório em arquivo xls. 

  <img src="" /> Possibilidade de enviar o arquivo via e-mail, selecionando uma das opções <img src="" />.

  <img src="" /> Tem a funcionalidade de organizar a visualização do relatório.   
   
<div id="rboletos" />
<b>R. Boletos</b> 


<center><i><font color = '#4889b1'>Relatório Boletos:</font></i></center>  

Relatório de boletos retorna todos os boletos gerados dentro do sistema.

<img src="" />

**a. Data:** Selecione entre as 3  opções para visualização <img src="" />.

**b. Dt. inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário. 

**c. Dt. final:** Data final automática do dia, mas poderá ser alterada. 

**d. Conta:** É possível selecionar a conta pela qual será emitida o relatório.

<div id="rcontasapagar" />
<b>R. Contas a pagar</b> 



<center><i><font color = '#4889b1'>Relatório Contas a pagar:</font></i></center> 

No relatório de contas a pagar, é possível identificar o lançamento de todas as contas a pagar do cartório.

<img src="" />

**a. Situação:** Poderá selecionar entre as 4 situações  <img src="" /> .

**b. Data:**  Possível selecionar entre as 3 datas  <img src="" />.

**c. Dt. inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário.

**d. Dt. final:** Data final automática do dia, mas poderá ser alterada caso necessário.

**e. Relatório:** Pode-se filtrar entre as 4 opções  <img src="" />. 

**f. Tipo:** Possibilidade de emissão por <img src="" />. 
     
<div id="rcontasareceber" />
<b>R. Contas a receber</b>

<center><i><font color = '#4889b1'>Relatório Contas a receber:</font></i></center> 

Relatório de contas a receber, são concentrados todas as contas a receber do cartório.

<img src="" /> 

Os campos tem as mesmas funcionalidades do relatório de contas a pagar, o que difere, que agora se trata do relatório de contas a receber.

<div id="rextratodecontas" />
<b>R. Extrato de contas</b>
 

<center><i><font color = '#4889b1'>Relatório Extrato de contas:</font></i></center> 

Possível visualizar registros de contas financeiras do cartório.

<img src="" /> 

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:** Data final do dia, mas poderá ser alterada.

**c. Situação:** Selecione entre as 3 situações ( Realizados, Previstos, Todos).

**d. Tipo:** Selecione entre os 2 tipos (Resumido ou Detalhado).

<img src="" />.

*Para filtrar uma determinada conta financeira, basta inserir os dados nas abas contas financeiras e formas de pagamento conforme exemplo abaixo:*

<img src="" />

<img src="" />

<div id="rextratodemensalistas" />
<b>R. Extrato de mensalistas</b>
   

<center><i><font color = '#4889b1'>Relatório Extrato de mensalistas:</font></i></center> 

Possível visualizar os registros dos mensalistas do cartório.

​                   ![R.Extrato_Mensalistas](C:\Users\Usuário\Desktop\BackupPC\Gislene\MANUAIS\Financeiro\R.Extrato_Mensalistas.PNG)

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:**  Data final do dia, mas poderá ser alterada.

<img src="" /> Não exibe no relatório os mensalistas com crédito.

<img src="" /> Não exibe o saldo anterior dos mensalistas no relatório.

Na aba *Clientes (Mensalistas)*  é possível filtrar por um determinado cliente.

<img src="" /> 

<div id="rfechamentodecaixa" />
<b>R. Fechamento de caixa</b>

<center><i><font color = '#4889b1'>Relatório Fechamento de caixa:</font></i></center> 

O fechamento de caixa consiste no retorno do processo diário de conferência das entradas e saídas do cartório.

<img src="" />    

**a. Dt. inicial:** Data inicial do dia, mas poderá ser alterada.

**b. Dt. final:** Data final do dia, mas poderá ser alterada.

**c. Relatório:** Selecione entre as 3 formas para apresentação <img src="" />.

**d. Atendente:** Emitir o relatório por um atendente em específico. <img src="" />

**e. Origem:** Selecione entre as 2 origem, Se foi praticado pelo caixa ou pelo balcão de notas <img src="" />. 

**f. Forma PG:** Selecione a forma que deseja visualizar no relatório,pois retorna no relatório apenas a forma de pagamento selecionada !<img src="" /> .

<img src="" /> Exibe o saldo anterior do caixa. 

<img src="" />

<img src="" /> Agrupa os atos por funcionário.

<img src="" /><img src="" /> Agrupa o plano de contas.

<img src="" />

<img src="" /> Exibe a taxa do cartão como uma saída no relatório.

<img src="" />

<img src="" /> Apresentadas apenas as contas "Caixa" entradas.

<img src="" /> Retorna as contas "Caixas" para saídas.

<img src="" /> Exibe as contas de resultado definidas no plano de contas como conta de resultado.

<img src="" /> Pagamentos com créditos de mensalista serão apresentados.

<img src="" /> Exibe troco devolvido ao cliente como uma saída no relatório. *Ex.: Valor total do recibo  58.83, valor recebido 60.00, troco 1.17 devolvido ao cliente*.

<img src="" />

<img src="" /> Exibe troco como entrada.

<div id="rlivroauxiliar" />
<b>R. Livro auxiliar</b>

<center><i><font color = '#4889b1'>Relatório Livro auxiliar:</font></i></center> 

Segundo a corregedoria do CNJ (*Conselho Nacional de Justiça*), a escrituração do livro auxiliar se trata da receita e da despesa pelos responsáveis pelas delegações do serviço extrajudicial de notas e de registro. 

Diante disso, o relatório livro auxiliar tem a finalidade de apresentar as receitas e despesas do cartório.

<img src="" />

<img src="" /> Termo de abertura  utilizado para assinatura digital do livro, se configurado pelo *(Menu > Cartório > Configurações > Aba Livros)*  é possível  criar um texto pre definido *(Texto criado conforme a necessidade do cartório)* , podendo criar o texto no termo de  abertura quanto no termo de encerramento conforme imagem a seguir:

<img src="" />

   

**Data do lançamento:** Data do dia do lançamento da despesa/receita <img src="" />.

**Tipo:** Selecione entre os 4 tipos <img src="" /> de acordo com a necessidade.

**Apuração:** Selecione a apuração correspondente <img src="" />.

**Complemento:** Complemento para colocar no livro auxiliar conforme provimento nº 45/2015. Nele é possível colocar o número do livro, folha inicial, folha final para controle interno <img src="" />. 

**Mais opções:**

<img src="" /> Exibe os emolumentos líquidos.

<img src="" /> Agrupa os códigos dos atos.

<img src="" /> Agrupa atos que tenha o mesmo código de tabela. *Ex.: Código da tabela 1401 Declaratória e 1401 Emancipação.*

<img src="" /> Exibe impressão sequencial dos atos pela data da pratica.

<img src="" /> Exibe o plano de contas nas despesas.

<img src="" /> O ato especial não será apresentado no relatório.

<img src="" /> Não exibe a quantidade de atos realizados.

<img src="" /> Acrescenta o valor do selo.

<img src="" /> Exibe o total por atribuição.

<img src="" /> Exibe a descrição da tabela de emolumentos.

<img src="" /> Exibe os atos gratuitos.

<img src="" /> Exibe o termo de abertura e encerramento.

<img src="" /> Seleciona os atos específicos para ser apresentados no relatório.

<img src="" />

<img src="" />

<div id="rlivrocaixa" />
<b>R. Livro caixa</b>

<center><i><font color = '#4889b1'>Relatório Livro caixa:</font></i></center> 

Relatório de livro caixa tem a finalidade de apresentar os rendimentos oriundos dos serviços notariais e cartoriais que serão tributados mensalmente pelo imposto de renda pessoa física(*IRPF*) .

<img src="" />
 *Gerar Documentos* <img src="" /> é possível gerar guia DARF/Exportar Carnê Leão.

**a. Data inicial:** Data inicial automática do dia, mas poderá ser alterada caso necessário. 

**b. Data final:** Data final automática do dia, mas poderá ser alterada caso necessário.

**c. Marcação PC:** Quando criado o plano de contas (*PC*) pelo (*Menu > Financeiro > Plano de contas*), com o campo *Marcação PC* preenchido, é possível filtrar essa marcação para ser apresentada no relatório.

<img src="" /> Agrupa plano de contas  na apresentação do relatório.

<img src="" /> Detalha as receitas por código da tabela.

<img src="" /> Detalha as receitas por código do recibo.

<img src="" /> O ato especial não será apresentado.

<img src="" /> Não será apresentado lançamentos que foi definido no plano de contas *(Menu > Financeiro > Plano de contas)*  como "Não dedutíveis".

<img src="" /> Exibe apenas contas que foram definidas como contas de resultado no plano de contas.  

<img src="" /> Exibe atos lançados no recibo (*Menu > Cartório > Recibos*) como depósito prévio.

<img src="" /> Exibe emolumentos líquidos.
   
<div id="rplanodecontas" />
<b>R. Plano de contas</b>

<center><i><font color = '#4889b1'>Relatório Plano de contas:</font></i></center> 

Relatório plano de contas, retorna todos os lançamentos praticados no cartório que foram definidos no  plano de contas (*Menu > Financeiro > Plano de contas*).

 <img src="" />

**Data:** Selecione entre as 4 datas (Lançamento, vencimento, pagamento, liquidação).

**Dt. inicial:** Data inicial do dia, mas poderá ser alterada se necessário.

**Dt. final:** Data final do dia, mas poderá ser alterada se necessário.

<img src="" /> Aplica somatório no início de cada grupo.

<img src="" /> Exibe somente contas que foram marcadas como contas de resultados na criação do plano de contas *(Menu > Financeiro > Plano de contas)*.

*Para visualizar apenas um plano de contas em específico, basta inserir o mesmo conforme imagem a seguir:* 

<img src="" />

Ao clicar em <img src="" /> será exibido o relatório como abaixo:

<img src="" />

<div id="rreceitadiária" />
<b>R. Receita diária</b>

<center><i><font color = '#4889b1'>Relatório Receita diária:</font></i></center> 

Relatório Receita diário exibe as receitas diárias do cartório.

<img src="" />

**Data inicial:** Data inicial do dia, mas poderá ser alterada se necessário.

**Data final:** Data final do dia, mas poderá ser alterada se necessário.

**Tipo:** Selecione entre os 4 tipos ( Resumido 1, Resumido 2, Detalhado 1, Detalhado 2).

**Ordem:** Selecione entre as 2 ordens ( Cód. tabela, Código).

**Atendente:** Será possível selecionar por um funcionário em específico.

**Origem:** Origem que foi realizado o ato. Se foi praticado pelo caixa ou pelo balcão de notas.

<img src="" />

<img src="" /> Não agrupa por atendente.

<img src="" /> Exibe recibos de mensalistas.

<img src="" /> Exibe saídas de caixa.

<img src="" /> Não exibe depósito prévio.

<img src="" /> Exibe adiantamentos de processos.

<img src="" /> Exibe pagamentos de mensalistas.

<img src="" /> Não exibe ato especial.

**Observações:** Ao preencher será exibida no relatório.

<img src="" />

<img src="" />



















 





















 
