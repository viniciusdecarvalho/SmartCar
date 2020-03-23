# SmartCar

#### Descrição

Aplicação para localizar e informar sobre preços e qualidade dos serviços prestados de distribuidoras/postos de combustíveis.

#### Requisitos Aplicativos Moveis
1. ##### Funcionais
	- *Listar Postos* - Aplicação deve listar distribuidoras/postos de combustíveis para um raio informado pelo usuário, com respectivos preços e avaliação. Também deve ser possível visualiza-los no mapa.
	- *Traçar Rota* - Aplicação deve traçar rota para a distribuidora/posto de combustível selecionado. 
	- *Registro e Login* - Usuários poderão realizar registro(Sign In) na aplicação e possibilitar entrar(Log In) posteriormente.
	- *Atualização manual* - Usuários da aplicação, quando entrar(logar) na aplicação,  poderão realizar atualização das informações de preços e avaliação através da aplicação.
	- *Carga periódica* - Aplicação deve consumir carga periódica de informações publicas dos preços de distribuidoras/postos de combustíveis disponibilizadas através da url http://www.anp.gov.br/images/infopreco/infopreco.csv`.
	- *Gasolina ou Álcool* - Aplicação deverá indicar qual o combustível mais vantajoso, calculando a proporção do preço e consumo do veiculo.
	- *Favoritos* - Usuários da aplicação, quando entrar(logar) na aplicação,  poderão incluir distribuidoras/postos na sua lista de Favoritos.
	- *Notificações* - Usuários da aplicação, quando entrar(logar) na aplicação,  receberão notificações, como mudança de preços dos Favoritos.
	- *Publicidade, Ads* - Aplicação deve possuir áreas de publicidade(Ads) com até 15% do display do dispositivo do usuário. A não exibição de publicidade(Ads), será possível através de pagamento via plataforma de pagamentos de cada dispositivo, inicialmente com valor de  R$5,99.
	- *Integração Auto* - Usuários da aplicação, poderão integrar funcionalidade com dispositivos dos automóveis, para utilização de funcionalidades de deslocamento por rota, e monitorar informação, como nível de combustível, para notificar sobre postos mais próximos e com preços mais baixos.   
2. ##### Não Funcionais
	- Aplicação deverá estar disponível para as plataformas Android e IOS
	- Aplicação deverá estar disponível somente para smartphones.
	- Aplicação deverá possuir identidade visual própria, contudo deve seguir recomendações de navegabilidade, e acessibilidade das plataformas as quais estejam disponíveis.
	- A atualização dos preços deverá manter as informações históricas realizadas anteriormente, tanto dos usuários quanto através de outras fontes.
	- Aplicação deverá permitir registro através de numero de telefone, APIs do Google e Facebook para tornar o processo mais ágil. Em ultimo caso utilizar Email. 
	- Aplicação deverá utilizar sistemas de deslocamento como Google Map e Waze, quando possível.
	- Aplicação deverá utilizar o menor custo possível com infraestrutura, se possível, um custo de acordo com a demanda.
	- Aplicação deverá estar disponível para instalação somente para usuário do território do Brasil. 

#### Modelagem com o Diagrama caso de uso
![DiagramaUsoGeral](https://github.com/viniciusdecarvalho/SmartCar/blob/master/projeto/diagrama_caso_uso_geral.png?raw=true "DiagramaUsoGeral")
