# Entrega - Estendendo o Oregon Trail com Herança

Neste Projeto, Oregon Trail usa herança para criar dois novos tipos de viajantes: `Hunter` (Caçador) e `Doctor` (Médico). Eles terão todas as outras características de qualquer outro Viajante, com essas diferenças:

## Hunter

Um Caçador é um Viajante que se dá melhor encontrando comida, mas também precisa de mais comida. Ele começa com 2 comidas em vez de apenas 1 como os outros viajantes. Ele também pode dar comida para outros viajantes:

### Método hunt()

Aumente a comida do caçador em 5. (Um viajante convencional ganha apenas 2.)

### Método eat()

Consome 2 unidades da comida do caçador. Se um caçador não tiver 2 comidas quando for instruído a comer, ele come o quanto puder (0 ou 1 unidade), mas o caçador não fica mais saudável. (Um viajante normal come apenas 1 unidade de comida.)

### Método giveFood(traveler, numOfFoodUnits)

Transfere numOfFoodUnits do caçador para outro viajante. Se o caçador tiver menos comida do que foi instruído a dar, então nenhuma comida é transferida.

## Doctor

Um médico é um viajante que se dá melhor curando outros viajantes, como médico ele deve curar outros viajantes para que eles possam seguir a viagem saudável. Ele possui apenas um método.

### Método heal(traveler)

Este método cura viajantes doentes fazendo com que eles sigam viagem saudáveis.Nesta etapa um viajante será passado como parâmetro para o método .heal(), para viajantes doentes, a propriedade isHealthy do viajante deverá mudar para true. Para viajantes que não estão doentes a saúde do mesmo, deve continuar como verdadeiro
