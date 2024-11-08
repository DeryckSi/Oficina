 ![deryck](https://github.com/user-attachments/assets/205b25c7-dbe6-4727-b049-f08e4453bb80)



<h1>Workshop_Model</h1>
Modelando um sistema de ordem de serviço de uma oficina usando MySQL Workbench.

<h3>Descrição: </h3>
Um sistema de controle que gerencia a execução de ordens de serviço em uma oficina mecânica.

Os consumidores levam seus veículos à oficina para serem reparados ou submetidos a uma revisão periódica.

Cada veículo é atribuído a uma equipe de mecânicos, que identifica os serviços necessários e preenche uma Ordem de Serviço (OS) com a data prevista para entrega.

Com base na OS, é calculado o valor de cada serviço, consultando-se uma tabela de referência de mão de obra.

O custo das peças também é incluído na OS.

A mesma equipe é responsável por avaliar e executar os serviços.



![oficina](https://github.com/user-attachments/assets/3985abf3-9beb-4eba-879c-edf7ee6dadc7)

<h3>Atributos:</h3>
Os mecânicos possúem código, nome, endereço e especialidade.

Cada OS possúi, numero, data de emissão, um valor, status e uma data para conclusão do trabalho.

<h3>Relacionamentos:</h3>
Uma OS pode compor vários serviços e um mesmo serviço pode estar contido em mais de uma OS.

Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.
