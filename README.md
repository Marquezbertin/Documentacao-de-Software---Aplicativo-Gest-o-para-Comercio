# Documentacao de Software - Aplicativo Gestão para Comercio
 
## Briefing
### Título do Projeto
Aplicativo Móvel para Comércio
Objetivo
Desenvolver um aplicativo móvel para comércios que apresentem funcionalidades essenciais,como cadastro de produtos, controle de estoque, pedidos via mensagem, registro de vendas, opções de pagamento (cartão, dinheiro e fiado), cadastro de clientes, geração de relatório(estoque, vendas e clientes devedores), visando facilitar e otimizar as operações do comércio.
### Descrição do Projeto
O objetivo deste projeto é criar um aplicativo móvel que atenda às necessidades básicas decomércios, permitindo o gerenciamento eficiente dos produtos, estoque, pedidos, vendas,clientes e pagamentos. O aplicativo será desenvolvido para dispositivos móveis, comosmartphones e tablets, utilizando uma abordagem de design responsivo para garantir umaexperiência de uso adequada em diferentes tamanhos de tela.
### Público-Alvo
O público-alvo do aplicativo móvel para comércios é composto por proprietários, gerentes efuncionários de pequenos e médios comércios, tais como lojas de varejo, mercados,restaurantes, lanchonetes, entre outros estabelecimentos semelhantes. Portanto, o aplicativo édirecionado a empreendedores e profissionais do setor comercial, que desejam otimizar efacilitar a gestão de seus negócios principalmente no que diz respeito ao controle de estoque, registro de vendas, pedidos, pagamentos e relacionamento com clientes.
Além disso, o aplicativo pode ser útil para clientes dessas transações, uma vez que permite o cadastro de informações de clientes, registro de pedidos e opções de pagamento diversificadas,como cartão de crédito, dinheiro e fiado. Portanto, o público-alvo também pode incluirconsumidores que desejam fazer pedidos de forma prática e acompanhar suas compras em estabelecimentos que utilizam o aplicativo.
É importante considerar que o aplicativo móvel deve ser desenvolvido levando em conta as características e necessidades desse público, oferecendo uma experiência de uso intuitiva,funcionalidades relevantes e uma interface amigável tanto para os comerciantes quanto para os clientes.
### Principais funcionalidades
* Cadastro de Produtos: 
Permitir o cadastro de produtos, incluindo informações como nome, descrição, preço,quantidade em estoque, fornecedor, etc.
Possibilitar a atualização e exclusão de produtos cadastrados.
* Entrada de Estoque de Produtos:
* Permitir o registro de entradas de estoque de produtos, informando a quantidade requerida e atualizando o saldo disponível no estoque.
* Pedidos via mensagem:
Oferecer aos clientes a opção de realizar pedidos por meio de mensagens, seja através de um chat interno no aplicativo ou utilizando serviços de mensagens externas, como WhatsApp.
* Registrar os pedidos recebidos, incluindo informações como produtos solicitados, quantidade,preço, dados do cliente, entre outros.
* Vendas: 
Registrar as vendas realizadas pelo aplicativo, incluindo os produtos vendidos, quantidade,preço unitário e total da venda.
Permitir a seleção dos clientes para associar as vendas realizadas.
#### Opções de pagamento
* 1-) Oferecer diferentes formas de pagamento, incluindo cartão de crédito, dinheiro e opção de fiado.
* 2-) Integrar o aplicativo com sistemas de pagamento online, como gateways de pagamento,para processar transações com cartão de crédito.
* 3-) Registrar vendas em dinheiro e permitir o cálculo do troco, quando necessário.
* 4-) Implementar uma função de “pendurar” ou “fiado” que permite ao comerciante registrar vendas sem pagamento imediato, mantendo um registro dos clientes devedores.
#### Cadastro de Clientes
Permitir o cadastro de clientes, incluindo informações como nome, endereço, telefone, e-mail,informações de pagamento e histórico de compras.
Possibilitar a atualização e exclusão de clientes cadastrados.
#### Geração de Relatórios
Gerar relação de relatório aos seguintes aspectos do comércio:
Relatório de Estoque: exibe a quantidade disponível de cada produto, permitindo a
identificação de produtos com estoque baixo e necessidade de reabastecimento.
Relatório de Vendas: apresente um resumo das vendas realizadas, incluindo o valor total das vendas, os produtos mais vendidos e os dados das transações.

* Relatório de Clientes Devedores: listar os clientes que possuem pendências financeiras,exibindo o valor devido e o histórico de compras não pagas.
### Considerações finais
O aplicativo móvel para negociações será desenvolvido com uma interface intuitiva e amigável, visando facilitar o uso pelos comerciantes e seus clientes. Será necessário integrar o aplicativo a sistemas externos, como gateways de pagamento, para garantir a efetivação das transações financeiras. Além disso, é importante implementar o controle de segurança para proteger os dados dos clientes e garantir a confiabilidade do aplicativo.
Este briefing servirá como base para o desenvolvimento do software, fornecendo uma visão geral das funcionalidades e objetivos do projeto. Com base nessas informações, a equipe de desenvolvimento poderá elaborar um plano detalhado, definir as tecnologias a serem utilizadas, estimar o tempo e os recursos necessários e iniciar o desenvolvimento do aplicativo móvel para comércios.

## Documento de Levantamento de Requisitos
#### Título do Projeto
Aplicativo Móvel para Comércio
* Dados
Cadastro de Produtos: 
Permitir o cadastro de produtos, incluindo informações como nome, descrição, preço,quantidade em estoque, fornecedor, etc.
* Entrada de Estoque de Produtos: 
Permitir o registro de entradas de estoque de produtos, informando a quantidade requerida e atualizando o saldo disponível no estoque.
* Pedidos via mensagem: 
Oferecer aos clientes a opção de realizar pedidos por meio de mensagens, seja através de um chat interno no aplicativo ou utilizando serviços de mensagens externas, como WhatsApp.
* Vendas: 
Registrar as vendas realizadas pelo aplicativo, incluindo os produtos vendidos, quantidade, preço unitário e total da venda.
#### Opções de pagamento
Oferecer diferentes formas de pagamento, incluindo cartão de crédito, dinheiro e opção de fiado.
#### Cadastro de Clientes
Permitir o cadastro de clientes, incluindo informações como nome, endereço, telefone, e-mail, informações de pagamento e histórico de compras.

##### Geração de Relatórios
Gerar relação de relatórios necessários a gestão do comércio.

#### Desenvolvimento
Bruno Bertin Marquez
#### Introdução
O objetivo deste documento é levantar e descrever os requisitos do aplicativo móvel para comércios. O aplicativo visa fornecer funcionalidades que facilitam a gestão de produtos, estoque, pedidos, vendas, clientes e pagamentos para comércios em geral.
#### Escopo do Projeto
#### Descrição do Aplicativo
O aplicativo móvel para comércios será desenvolvido para dispositivos móveis, como
smartphones e tablets. Ele terá uma interface intuitiva e fácil de usar, proporcionando uma experiência amigável para os usuários.
#### Funcionalidades Principais
O aplicativo terá as seguintes funcionalidades principais:
* Cadastro de Produtos: 
Os usuários poderão se cadastrar nos produtos disponíveis em suas negociações.
As informações dos produtos a serem cadastradas incluem nome, descrição, código, preço,categoria, fornecedor, entre outros.
* Entrada de Estoque de Produtos: 
Os usuários podem registrar a entrada de novos produtos em seu estoque.
Será necessário informar a quantidade, dados e fornecedor da entrada de estoque.
* Pedidos via Mensagem:
Os clientes podem realizar pedidos por meio de mensagens no aplicativo.
Os usuários podem visualizar e gerenciar esses pedidos, incluindo a confirmação, preparação e entrega.
* Vendas: 
Os usuários poderão registrar as vendas realizadas em seus negócios.
Será necessário informar os produtos vendidos, quantidade, dados, forma de pagamento e cliente.
* Formas de Pagamento: 
O aplicativo terá suporte para pagamento por cartão e dinheiro.
Os usuários poderão selecionar a forma de pagamento utilizada em cada venda.
* Função de Pendurar (Fiado):
O aplicativo permitirá que os usuários registrem vendas a crédito para clientes.
Será necessário registrar o valor da venda, cliente e dados de vencimento.
* Cadastro de Clientes: 
Os usuários poderão cadastrar informações dos clientes, como nome, telefone, endereço, entreoutros.
Esses dados serão usados para registro de vendas, pedidos e controle de pendências.
* Relatórios:
O aplicativo fornecerá funcionalidades para geração de relatórios.
Será possível gerar relatório de estoque, vendas realizadas e clientes que estão desenvolvendo.
#### Requisitos Não Funcionais
Além das funcionalidades descritas, o aplicativo deve atender aos seguintes requisitos não funcionais:
#### Plataformas e Dispositivos Suportados
O aplicativo deve ser com dispositivos móveis compatíveis que executam os sistemas
operacionais iOS e Android.
* Segurança: 
O aplicativo deve garantir a segurança dos dados dos usuários e clientes.
As informações sensíveis devem ser armazenadas de forma criptografada.
* Desempenho:
O aplicativo deve ser rápido e responsivo, mesmo em situações de alto volume de dados.
O tempo de resposta das principais funcionalidades não deve ser superior a 3 segundos.
Usabilidade
O aplicativo deve ser intuitivo e fácil de usar, mesmo para usuários inexperientes.
A interface do usuário deve ser clara, com elementos visuais bem organizados e legíveis.
#### Restrições Técnicas
O aplicativo deve atender às seguintes restrições técnicas:
Linguagem de Programação e Frameworks.
O desenvolvimento do aplicativo será realizado utilizando a linguagem de programação Kotlin, acompanhado de Frameworks como Kotlin Multiplatform Mobile, Flutter ou NativeScript para agilizar o desenvolvimento e garantir a eficiência do código.
#### Banco de Dados
O aplicativo requer um banco de dados para armazenar as informações dos produtos, estoque, clientes e vendas.
Será utilizado SQLite, que é com as tecnologias selecionadas e oferece suporte adequado paraa escalabilidade e segurança dos dados.

#### Integrações
O aplicativo poderá exigir integrações com outros sistemas ou APIs para funcionalidades específicas, como processamento de pagamentos.
As integrações serão realizadas utilizando Twilio API for WhatsApp, Stripe, de acordo com as necessidades identificadas durante o processo de desenvolvimento.
#### Plataformas e Requisitos de Sistema
O aplicativo será desenvolvido para dispositivos móveis nas plataformas iOS e Android.
Serão considerados os requisitos de sistema mínimos para garantir que o aplicativo seja executado corretamente nos dispositivos móveis mais comuns, incluindo versões de sistema operacional compatível, capacidade de armazenamento e requisitos de memória.
#### Arquitetura
O aplicativo seguirá uma arquitetura de desenvolvimento em camadas (por exemplo, MVC,MVVM, etc.) para garantir a separação de responsabilidades e a modularidade do código.
#### Testes
Serão realizados testes unitários, de integração e de recepção para verificar a qualidade efuncionalidade do aplicativo.
Será utilizada uma estratégia de testes adequada para garantir a cobertura abrangente e a detecção de possíveis erros e falhas.
É importante considerar essas restrições técnicas ao longo do processo de desenvolvimento para garantir a eficiência, desempenho e compatibilidade do aplicativo móvel para comércios.
#### Conclusão
Este levantamento de requisitos para o aplicativo móvel de comércio apresentou como funcionalidades principais, requisitos não funcionais e restrições técnicas necessárias para o desenvolvimento do sistema. O objetivo do aplicativo é facilitar a gestão de produtos, estoque, pedidos, vendas, clientes e pagamentos para comércios em geral.
As principais funcionalidades incluem cadastro de produtos, entrada de estoque,pedidos via mensagem, registro de vendas, formas de pagamento, função de pendurar (fiado), cadastro declientes e geração de relatório. Essas funcionalidades visam atender às necessidades dos usuários e melhorar a eficiência das operações comerciais.
Além disso, foram identificados requisitos não funcionais importantes, como suporte adispositivos móveis iOS e Android, segurança dos dados, desempenho responsivo, usabilidade intuitiva e clareza na interface do usuário.
As restrições técnicas definem a linguagem de programação e frameworks a serem utilizados, o banco de dados necessário, possíveis integrações com sistemas externos e requisitos de sistema para compatibilidade com dispositivos móveis. A arquitetura do aplicativo seguirá uma abordagem para garantir a modularidade e a separação de responsabilidades.
Ao considerar todos esses requisitos e restrições, é possível desenvolver um aplicativo móvel para comércio eficiente, seguro e intuitivo. É importante realizar testes abrangentes para garantir a qualidade e funcionalidade do sistema, levando em conta as necessidades dos usuários e os objetivos comerciais.
Com base neste levantamento de requisitos, a equipe de desenvolvimento poderá iniciar o processo de design, implementação e testes do aplicativo móvel para comércio, buscando atender às expectativas e necessidades dos usuários finais.
## Documento de Descrição dos Casos de Uso: Aplicativo Móvel para Comércio
#### Caso de Uso: Login no Aplicativo Móvel
#### Descrição
O caso de uso de login permite aos usuários acessar o aplicativo móvel utilizando seu CNPJ (Cadastro Nacional da Pessoa Jurídica) e senha cadastrada. O login é necessário para garantir a segurança e o login dos usuários antes de utilizarem as funcionalidades do aplicativo.
#### Ator Principal
Usuário
#### Fluxo Principal:
1-) O usuário abre o aplicativo móvel.
2-) O aplicativo exibe uma tela de login.
3-) O usuário insere o CNPJ da empresa.
4-) O usuário insere uma senha cadastrada.
5-) O usuário seleciona a opção de login.
6-) O sistema verifica as informações de login fornecidas.
7-) O sistema autêntica o usuário.
8-) O sistema redireciona o usuário para a página inicial do aplicativo.
#### Fluxo Alternativo
No passo 6, se as informações de login estiverem incorretas, o sistema exibe uma mensagem de erro e permite que o usuário tente novamente.
#### Pré-condições
O aplicativo móvel está instalado no dispositivo do usuário.
O usuário possui um CNPJ registrado e uma senha cadastrada no sistema.
#### Pós-condições
O usuário é autenticado com sucesso e tem acesso às funcionalidades do aplicativo.

* Observações
Caso o usuário não tenha um CNPJ registrado ou tenha esquecido a senha, o caso de uso pode ser projetado para incluir a funcionalidade de recuperação de senha ou criação de uma nova conta.
#### Caso de Uso: Cadastro de Produtos no Aplicativo de Comércio Eletrônico
Este casode uso descreve como os usuários podem cadastrar novos produtos no aplicativo de comércio eletrônico. Os usuários têm a capacidade defornecer informações específicas, como nome do produto, descrição, preço, categoria e
imagem, para facilitar a visualização e busca dos produtos pelos clientes.
#### Ator principal
Usuário do aplicativo de comércio eletrônico
#### Pré-condições
O usuário está autenticado no aplicativo.
O usuário possui permissões adequadas para cadastrar produtos.
#### Fluxo principal:
1-) O usuário seleciona a opção de "Cadastro de Produtos" no aplicativo.
2-) O sistema exibe um formulário de cadastro de produtos.
3-) O usuário preenche os seguintes campos:
3.a-) Nome do produto: O usuário insira o nome do produto desejado.
3.b-) Descrição: O usuário fornece uma descrição detalhada do produto, destacando suas características, funcionalidades e benefícios.
3.c-) Preço: O usuário especifica o preço do produto.
3.d-) Categoria: O usuário seleciona a categoria à qual o produto pertence, como eletrônico, vestuário, alimentos, etc.
3.e-) Imagem do produto: O usuário faz o upload de uma imagem do produto, que será
exibida na página de detalhes do produto.
4-) O sistema salva as informações do produto no banco de dados.
5-) O sistema gera um identificador único para o produto cadastrado, que pode ser um número
sequencial, um código alfanumérico ou qualquer outra forma de identificação única.
6-) O sistema exibe uma mensagem de confirmação informando ao usuário que o produto foi cadastrado com sucesso, acompanhado de o identificador único gerado.
7-) O usuário tem a opção de adicionar mais produtos, selecionando a opção “Adicionar Novo Produto” no aplicativo.
8-) Caso o usuário não queira adicionar mais produtos, ele pode selecionar a opção “Finalizar” para encerrar o processo de cadastro de produtos.
9-) O sistema redireciona o usuário de volta à página principal do aplicativo, onde ele pode visualizar uma lista de produtos cadastrados, realizar outras ações no aplicativo ou sair da sessão, conforme necessário.
10-) O usuário concluiu o cadastro de produtos no aplicativo e agora pode disponibilizá-los para venda ou visualização pelos clientes.
11-) O sistema armazena os dados do produto no banco de dados de forma persistente, para que as informações estejam disponíveis mesmo após o encerramento da sessão do usuário.
Isso permite que os produtos cadastrados sejam utilizados em outras funcionalidades do aplicativo, como exibição na página de busca, recomendações de produtos relacionados, entre outras.
12-) Os produtos cadastrados ficam disponíveis para os clientes visualizarem e adquirirem no aplicativo. Essa funcionalidade permite que os clientes pesquisem e encontrem os produtos desejados, utilizando filtros de busca, categorias e outros critérios de pesquisa.
Além disso, os produtos cadastrados podem ser gerenciados pelo usuário, permitindo que ele faça alterações nas informações, como atualização do preço, descrição, categoria ou imagem do produto, caso seja necessário.
13-) O sistema também pode oferecer recursos adicionais, como a possibilidade de o usuário monitorar o estoque dos produtos cadastrados, receber notificações sobre vendas ou internamente dos clientes com os produtos, e gerar relatório de desempenho das vendas, auxiliando o usuário na gestão do seu negócio.
14-) Em caso de necessidade de exclusão de um produto cadastrado, o usuário pode selecionar a opção de “Excluir Produto” no aplicativo. O sistema solicitará a confirmação do usuário antes de realizar a exclusão definitiva do produto do banco de dados. Após a confirmação, o produto será removido e não estará mais disponível para visualização ou compra pelos clientes.
15-) O usuário concluiu o cadastro de produtos no aplicativo, os produtos estão disponíveis para visualização e compra pelos clientes, e o usuário tem a possibilidade de gerenciar, atualizar ou excluir os produtos conforme necessário.
16-) O caso de uso é concluído. O usuário foi capaz de cadastrar novos produtos no aplicativo,fornecendo informações como nome, descrição, preço, categoria e imagem do produto. Essa funcionalidade permite que os produtos sejam disponibilizados aos clientes, ampliando asopções de compra no aplicativo de comércio eletrônico.
#### Caso de Uso: Registrar Entrada de Estoque de Produtos no Aplicativo de Comércio Eletrônico
* Ator Principal
Usuário
#### Resumo
Este caso de uso descreve o processo de registro de uma entrada de novos produtos no estoque do comércio. O usuário deve inserir informações como o código do produto, a quantidade recebida, a data de entrada e, opcionalmente, o fornecedor. Após o registro, o estoque será atualizado de acordo com a quantidade de produtos adicionados.
#### Fluxo Básico
1-) O caso de uso começa quando o usuário seleciona uma opção de registrar uma entrada de estoque de produtos.
2-) O sistema exibe um formulário de registro de entrada de estoque, solicitando as seguintes informações:
2.a-) Código do produto: O usuário insere o código identificador único do produto.
2.b-). Quantidade recebida: O usuário insere a quantidade de produtos recebidos.
2.c-) Dados de entrada: O usuário insere um dado em que os produtos foram recebidos.
2.d-) Fornecedor (opcional): O usuário pode inserir o nome do fornecedor dos produtos.
3-) O usuário preenche todas as informações solicitadas.
4-) O sistema valida os dados inseridos pelo usuário.
5-) O sistema atualiza o estoque de acordo com a quantidade de produtos adicionados.
6-) O sistema registra a entrada de estoque no histórico, armazenando as informações da entrada, como o código do produto, a quantidade recebida, a data de entrada e o fornecedor (se fornecido).
7-) O sistema exibe uma mensagem de confirmação, informando que a entrada de estoque foi registrada com sucesso.
#### Fluxo Alternativo:
1-) O usuário decide cancelar o registro da entrada de estoque: O caso de uso é encerrado.
2-) O sistema não consegue atualizar o estoque: O sistema exibe uma mensagem de erro,
informando que a entrada de estoque não pôde ser registrada. 2. O caso de uso é fechado.
Extensões:
- Possibilidade de adicionar validações adicionais nos passos 4 e 5 para garantir a integridade
dos dados e o cumprimento de regras específicas do negócio.
- Possibilidade de notificar automaticamente o fornecedor sobre a entrada de estoque, caso o
fornecedor tenha sido fornecido.
- Possibilidade de realizar verificações de disponibilidade de espaço físico no estoque antes de registrar a entrada.
#### Caso de Uso: Pedidos via mensagem no Aplicativo de Comércio Eletrônico
* Ator principal: 
Usuário
Interessados
Sistema de pedidos,Sistema de catálogo
#### Pré-condições:
O usuário deve estar registrado e autenticado no aplicativo.
O catálogo de produtos deve estar disponível no sistema.
#### Fluxo principal de eventos
1-) O usuário acessa o aplicativo e inicia a funcionalidade de pedidos via mensagem.
2-) O sistema exibe o catálogo de produtos disponíveis para o usuário.
3-)O usuário navega pelo catálogo e seleciona os produtos desejados.
4-) Para cada produto selecionado, o usuário indica a quantidade desejada.
5-) O usuário pode adicionar informações adicionais relevantes, como instruções de entrega, em um campo de texto.
6-) O usuário revisa o pedido para garantir que os itens estejam corretos.
7-) O usuário envia o pedido por meio de uma mensagem.
8-) O sistema registra o pedido e gera um número de pedido único.
9-) O sistema confirma o recebimento do pedido para o usuário.
10-) O sistema encaminha o pedido para processamento, incluindo o registro das informações adicionais fornecidas pelo usuário.
11-) O sistema atualiza o status do pedido para "pendente" e inicia o processamento.
#### Fluxo alternativo:
1-) O usuário decide remover um item do pedido:
2-) O usuário seleciona o item que deseja remover.
3-) O sistema remove o item do pedido e atualiza o total.
4-) O sistema não consegue processar o pedido:
5-) O sistema exibe uma mensagem de erro informando o usuário sobre o problema.
6-) O usuário pode tentar enviar o pedido novamente ou entrar em contato com o suporte para obter assistência.
#### Pós-condições
- O sistema registra o pedido no sistema.
- O status do pedido é atualizado para "pendente".
- O usuário recebe uma confirmação do recebimento do pedido.
#### Requisitos não funcionais
1-) O sistema deve fornecer uma interface intuitiva e fácil de usar para navegar pelo catálogo de produtos.
2-) O sistema deve processar e confirmar o pedido em tempo hábil.
3-) O sistema deve ser capaz de lidar com vários pedidos simultaneamente.
4-) O sistema deve armazenar as informações do pedido, incluindo os produtos selecionados, instruções e instruções adicionais.
#### Descrição de outras funcionalidades e casos de uso Vendas.
Este caso de uso permite aos usuários registrar vendas realizadas. Eles podem selecionar os produtos vendidos a partir do catálogo disponível, indicar a quantidade vendida e o preço unitário. O sistema calculará automaticamente o valor total da venda. Os usuários também podem registrar o tipo de pagamento, como cartão de crédito, dinheiro ou pendurar (fiado). Os dados da venda serão armazenados para fins de relatório.
* Cartão; 
Esta função permite aos usuários realizar pagamentos por meio de cartão de crédito ou débito.
Os usuários devem fornecer as informações necessárias do cartão, como número, validade e
código de segurança. O sistema realizará a transação de pagamento e registrará os detalhes da transação para fins de contabilidade.
* Dinheiro; 
Este caso de uso permite aos usuários registrar pagamentos em dinheiro recebido durante as vendas. Os usuários devem inserir o valor em dinheiro recebido e o sistema atualizará o valor total da venda e registrará os detalhes do pagamento.
* Função de pendurar (fiado)
Esta função permite aos usuários oferecer a opção de pendurar uma venda, ou seja, permitir que o cliente compre os produtos e pague em uma data futura. Os usuários devem registrar os detalhes da venda e selecionar a opção de pendurar. O sistema manterá um registro das vendas penduradas para acompanhamento posterior.
* Cadastrar Clientes
Este caso de uso permite aos usuários cadastrar novos clientes no aplicativo. Os usuários devem fornecer informações como nome do cliente, endereço, número de telefone e outras informações relevantes. O sistema armazenará os detalhes do cliente para referência futura, como no caso de acompanhamento de vendas penduradas.
* Fazer relatório; 
Neste caso de uso, os usuários podem gerar relatórios com base nas informações armazenadas no aplicativo. Os relatórios podem incluir dados de vendas, informações de estoque, clientes que estão desenvolvendo, entre outros. Os usuários podem especificar os critérios para o relatório, como um intervalo de dados ou uma categoria específica de produtos.
* Estoque; 
Este caso de uso permite aos usuários visualizar o estoque atualizado dos produtos
disponíveis. Eles podem verificar a quantidade de cada produto, seu status (disponível,esgotado, etc.) e outras informações relevantes. Isso ajuda os usuários a tomar decisões sobre pedidos de estoque.
* Clientes que estão devendo;
Este caso de uso permite aos os usuários visualizam uma lista de clientes que possuem pendências financeiras, ou seja, que estão desenvolvendo ao comércio. O sistema fornecerá informações sobre o valor total da dívida de cada cliente e o histórico de vendas penduradas.
Isso auxilia os usuários a monitorar e gerenciar os pagamentos em atraso, permitindo ações como entrar em contato com os clientes para cobranças ou estabelecer acordos de pagamento.
* Clientes que estão se desenvolvendo; 
O aplicativo móvel para comércio descrito acima oferece uma ampla gama de funcionalidades que facilitam a gestão de produtos, vendas, estoque e relacionamento com clientes. Ele permite que os usuários cadastrem produtos, gerenciem a entrada de estoque, recebam pedidos via mensagem, registrem vendas com diferentes formas de pagamento (cartão ou dinheiro), controlem a opção de venda fiado, cadastrem clientes, gerem relatório sobre vendas,estoque e clientes inadimplentes. Essas funcionalidades são projetadas para auxiliar os usuários na administração eficiente de um negócio de comércio, fornecendo ferramentas para
gerenciar o estoque, acompanhar vendas, controlar pendências financeiras e fornecer um bom atendimento aos clientes.
#### Resumo
Ao longo do processo de documentos do projeto do aplicativo móvel para comércios, foram elaborados os seguintes documentos:
* Briefing;
O briefing forneceu uma visão geral do projeto, destacando seu objetivo, público-alvo e principais funcionalidades. Isso criou uma base sólida para o desenvolvimento do aplicativo, garantindo que as necessidades e expectativas dos usuários fossem consideradas desde o início.
* Levantamento de Requisitos;
O levantamento de requisitos identificados e documentou os requisitos específicos do aplicativo móvel para transações. Isso incluía como funcionalidades essenciais, como cadastro de produtos, controle de estoque, pedidos via mensagem, vendas com opções de pagamento em cartão ou dinheiro, função de pendurar fiado, cadastro de clientes e geração de relatório.
Além disso, foram considerados aspectos como a usabilidade, segurança e integração com outros sistemas, proporcionando uma visão detalhada do que o aplicativo precisa entregar.
* Casos de Uso; 
Casos de uso são uma técnica utilizada no desenvolvimento de sistemas para descrever como o sistema será utilizado pelos usuários finais. Eles descrevem relaxantes entre o sistema e os atores (usuários ou outros sistemas) que estão envolvidos no processo.

Os casos de uso são uma forma de capturar requisitos funcionais do sistema, ou seja, descrevem o que o sistema deve fazer em termos de funcionalidades e perfeitamente com os usuários. Eles fornecem uma visão detalhada de como o sistema se comportará em diferentes cenários de uso.

Cada caso de uso geralmente descreve uma sequência de ações que um usuário ou ator realiza para alcançar um objetivo específico usando o sistema. Eles são geralmente representados em forma de diagramas de casos de uso, que mostram os atores envolvidos, os casos de uso individuais e as relações entre eles.

Os casos de uso são uma ferramenta importante para a comunicação entre desenvolvedores, clientes e finais, pois ajudam a garantir que todos tenham uma compreensão comum das funcionalidades e comportamentos do sistema. Eles também podem servir como base para a criação de testículos e validação do sistema durante o processo de desenvolvimento.

Em resumo, os casos de uso descrevem como relaxantes entre usuários e sistemas, fornecendo uma visão clara dos requisitos do habilidades
