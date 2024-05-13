## Trabalhando com Machine Learning na Prática no Azure ML

### Project - TO DO

 - [x] Crie um novo repositório no github com um nome a sua preferência
 - [x] Crie um modelo de previsão com seus devidos pontos de extremidade configurados
 - [x] Escreva o passo a passo desse processo em um readme.md de como você chegou nessa etapa
 - [x] Salve nesse repositório o readme.md e o arquivo .json de pontos de extremidade
 - [x] Compartilhe conosco o link desse repositório através do botão 'entregar projeto'

### Passo a Passo

Primeiramente, é necessário criar um recurso de Azure Machine Learning através do Portal do Azure.
!(alt)[1.png]

No estúdio, crie um espaço de trabalho. Uma vez criado, acesse o espaço de trabalho e, na barra lateral à esquerda, selecione ML automatizado.
!(alt)[11.png]

Escolha a opção Novo trabalho de ML automatizado e preencha os campos de acordo com as orientações da documentação da Microsoft.
!(alt)[2.png]

Durante a configuração do trabalho, crie uma nova fonte de dados. As instruções para a criação da fonte de dados estão disponíveis na documentação, e a Microsoft fornece um arquivo csv com dados históricos de aluguel de bicicletas -> https://aka.ms/bike-rentals.
!(alt)[3.png]

Em Configurações adicionais, desmarque a opção Usar todos os modelos suportados e, em seguida, selecione apenas os modelos RandomForest e LightGBM.
!(alt)[4.png]

Expanda a seção de Limites e configure conforme indicado abaixo.
!(alt)[5.png]

Finalmente, defina a validação e o teste conforme descrito abaixo.
!(alt)[6.png]

Infelizmente, não foi possível prosseguir com este desafio, pois os créditos gratuitos se esgotaram, e ao limitar os recursos para evitar gastos, o Azure não consegue completar o trabalho.

### Reflexões e Conclusões
Apesar de não ter conseguido concluir meu trabalho de regressão no Azure Machine Learning Studio devido à falta de créditos, o processo foi extremamente valioso. Adquiri um profundo entendimento teórico e habilidades práticas importantes em ciência de dados, o que considero um avanço significativo no meu aprendizado.
