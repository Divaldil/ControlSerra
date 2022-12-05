# ControlSerra
## **Projeto para Engenharia de Software II**

### Nome dos membros:
* [Antonio Carlos](https://github.com/antonioN313)
* [Henrique Vidotto](https://github.com/HenriqueVidotto) 
* [Matheus Divaldil](https://github.com/Divaldil)
* [Guilherme Fidalgo](https://github.com/Pepelepew0000)


**Resumo do Projeto**
--
  O projeto será um sistema de gerenciamento de uma serralheria onde teremos o controle de estoque, criação de orçamento, e relatórios de materiais e de produtos. O sistema possuirá uma tela de menu principal, que permitirá o acesso às demais telas do projeto, com diversas telas de cadastro para fornecedores e clientes.

  Primeiramente o sistema possuirá uma tela para visualizar, alterar e criar orçamentos, as quais permite calcular os gastos para cada serviço. Um mesmo cliente poderá ter vários orçamentos ligados a ele. A partir dos dados inseridos nesta tela o usuário poderá gerar um relatório em forma de impressão ou PDF, o qual poderá ser enviado para os seus clientes. Cada orçamento é numerado para facilitar a gestão de dados para a tomada de decisão.

  Em seguida, o sistema possuirá uma tela para comparar os diversos valores dos materiais, disponibilizando de várias tabelas que serão utilizadas para cada serviço solicitado pelos clientes, possuindo orçamentos separados ligados a estas. Estas tabelas permitem comparar os valores para cada tipo material com cada fornecedor registrado no sistema. 

  O sistema também disponibilizará de uma tela para controle de estoque, a qual permite cadastrar produtos, inserir os seus nomes, seus preços, suas quantidades, seus tipos e suas unidades de medida. Cada tipo de produto terá um código que será gerado automaticamente.

  Haverá uma tela para os cálculos de materiais que serão utilizados nos serviços, os quais serão divididos em várias tabelas separadas para cada orçamento, e os seus dados também serão utilizados para auxiliar nos orçamentos. Estas telas vão possuir uma ligação direta com os dados das tabelas de comparação de valores. Os resultados destes cálculos retornarão as quantidades de materiais que serão utilizadas, das barras e dos gastos com cada unidade, podendo serem impressos para serem enviados em forma de relatório de compras para os fornecedores.

  Haverá uma tela para cadastro de clientes e de fornecedores, em que teremos os dados básicos, como nomes, endereços, contatos, entre outros. 

  Outra funcionalidade importante do sistema são os cálculos para certas peças, os quais serão feitos através de uma tela que possui fórmulas específicas para os tipos de peças que foram registradas no sistema. As formulas estarão presentes no programa de inicio, e variam dependendo do padrão selecionado. A partir destes cálculos, será possível realizar relatórios dos resultados, os quais serão destinados para complementar os serviços dos orçamentos. 

  O sistema precisará ter uma tela dedicada para os cálculos das sobras das barras utilizadas para o serviço. Esta tela servirá para auxiliar nas medidas dos cortes e também permite visualizar a quantidade restante das barras, medidas em metros, para serem reaproveitadas no serviço.

  O sistema também utilizará um banco de dados que estará conectado ao sistema diretamente e poderá ser manipulado para armazenar os dados do estoque e dos orçamentos em tabelas. Os dados serão atualizados automaticamente para cada alteração.



### Tecnologias que serão utilizadas 
1. C# 
2. Visual Studio 2022 
3. .NET 
4. SQL server
