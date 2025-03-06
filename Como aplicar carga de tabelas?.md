## Como aplicar uma carga de tabelas? 


#### *Escopo de configuração do time de suporte: O processo abaixo é realizado mediante solicitação do parceiro/cliente final, sempre que houver necessidade de atualizar os parâmetros de configuração da loja, ou ainda para corrigir erros pontuais.

#### O que são as tabelas? 
##### Hoje temos disponíveis no mercado várias bandeiras e modalidades de cartão e configurar todas as opções levaria dias até mesmo meses. Pensando em otimizar esse fluxo foi criada uma transação de Carga de Tabelas que consiste em “baixar” para o SiTef todas as configurações da rede Adquirente por meio de tabelas. Essas tabelas consistem de informações e configuração das transações que estão liberadas para cada cartão, cliente e estabelecimento. É essa carga de configurações que permitirá o cliente trabalhar com X ou Y cartão disponível hoje no mercado.


##### 1. Acesse o portal da Fiserv, através do link: "https://sitefexpressadm.softwareexpress.com.br/sitefwebadm/pages/inicial.zeus"; e em seguida, acesse o configurador sitef.

<img src="https://github.com/TefElgin/SITEF-ELGIN/blob/a112e2c4bd0dc470ed925684ba2749e10891873a/Imagens/1.Associacao%20de%20combust%C3%ADveis/1.interface%20do%20portal.png"  width="850">

##### 2. Selecione o servidor Elgin.SA.

<img src="https://github.com/TefElgin/SITEF-ELGIN/blob/a112e2c4bd0dc470ed925684ba2749e10891873a/Imagens/1.Associacao%20de%20combust%C3%ADveis/2.acessar_configurador.png" width="850">


##### 3. Selecione o módulo objeto da aplicação de carga de tabelas.

<img src="https://github.com/TefElgin/SITEF-ELGIN/blob/847020e9e0f50dc6e4972f4dcea1e52e066d3133/Imagens/2.%20Carga%20de%20tabelas/2_modulo.png" width="850">


##### 3. No campo "Empresa", inserir o código da loja, clicar na opção ao lado do código da loja, de modo que seja exibido um símbolo de seleção. Após isso, basta clicar em "ENVIAR", para aplicar a carga de tabelas(vide imagem abaixo).

<img src="https://github.com/TefElgin/SITEF-ELGIN/blob/847020e9e0f50dc6e4972f4dcea1e52e066d3133/Imagens/2.%20Carga%20de%20tabelas/3_sucesso.png" width="850">

##### O resultado é exibido ao final do processo, devendo retornar apenas "OK". 

#### Ao final da aplicação da carga de tabelas, é possível "forçar" a aplicação da carga no terminal. Segue abaixo o procedimento para aplicação:

#### *DLL: Basta acessar o diretório c:/clisitef, apagar a pasta ChavesClisitef; reiniciar a aplicação comercial(sistema de vendas) e aplicar uma nova carga de tabelas, sendo possível também, realizar apenas uma nova transação.


#### *TROCA DE ARQUIVOS: Basta acessar o diretório C:/Cliente, apagar a pasta ChavesBiblPinPad e aplicar uma nova carga de tabelas via MODULAR.




