# Bootcamp - Programação C# com CRM Dynamics
## Projeto - Dio-Sistema-Estacionamento: Entrega desafio de projeto

### Proposta
construir uma classe chamada "Estacionamento":
A classe contém três variáveis, sendo:

precoInicial: Tipo decimal. É o preço cobrado para deixar seu veículo estacionado.

precoPorHora: Tipo decimal. É o preço por hora que o veículo permanecer estacionado.

veiculos: É uma lista de string, representando uma coleção de veículos estacionados. Contém apenas a placa do veículo.

A classe contém três métodos, sendo:

AdicionarVeiculo: Método responsável por receber uma placa digitada pelo usuário e guardar na variável veiculos.

RemoverVeiculo: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: precoInicial * precoPorHora, exibindo para o usuário.

ListarVeiculos: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Por último, deverá ser feito um menu interativo com as seguintes ações implementadas:

Cadastrar veículo
Remover veículo
Listar veículos
Encerrar
