# Padrão Mediator
O Mediator é um padrão comportamental que reduz o acoplamento entre os componentes de um programa, fazendo-os se comunicar indiretamente, por meio de um objeto mediador especial.

## Exemplo conceitual

#### Sistema de tráfego de estação ferroviária:

- Dois trens nunca se comunicam entre si
- ```stationManager``` atua como mediador e disponibiliza a plataforma para apenas um dos trens que chegam
- Mantém os demais trens em uma fila
- Um trem partindo notifica as estações, o que permite que o próximo trem na fila chegue
