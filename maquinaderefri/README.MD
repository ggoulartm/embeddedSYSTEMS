# Projeto de uma FSM de Sistema Embarcado C++ para Máquina de Refrigerante

	A ideia do projeto é desenvolver o sistema da máquina de refrigerante, com duas opções de refrigerante: meet e etirps.

	A interface de usuário diz qual o saldo presente na máquina e há quatro opções de comando para o usuário:
		Inserir moedas nos valores de R$ 0,25; R$ 0,50 ou R$ 1,00
		Devolver o valor total, ou parcial, caso o saldo ultrapasse R$ 1,50
		Pegar Refrigerante Meet
		Pegar Refrigerante Etirps

![Diagrama de Estados](https://github.com/ggoulartm/embeddedSYSTEMS/blob/C++sistemasEmbarcados/maquinaderefri/Diagrama%20de%20Estados.png?raw=true)


## Implementação

A implementação deste modelo consiste em 3 arquivos:

	fsm.cpp:
		contém as funções da máquina de estados

	IO.cpp
		contém as classes referentes ao ambiente no qual o sistema embarcado irá operar

	main_fsm.cpp
		reúne os arquivos do projeto e o loop do sistema

