# Spaceship Titanic
* Objetivo:
    predecir si un pasajero fue transportado a una dimensión alternativa durante la colisión de la nave espacial Titanic con la anomalía del espacio-tiempo. 

* Descripciones de archivos y campos de datos

* train.csv - Registros personales de aproximadamente dos tercios (~8700) de los pasajeros, que se utilizarán como datos de entrenamiento.
    PassengerId - Un ID único para cada pasajero. Cada ID tiene la forma en la que indica un grupo con el que viaja el pasajero y es su número dentro del grupo. Las personas de un grupo suelen ser miembros de la familia, pero no siempre.gggg_ppggggpp
    HomePlanet - El planeta del que partió el pasajero, normalmente su planeta de residencia permanente.
    CryoSleep - Indica si el pasajero ha optado por ser puesto en animación suspendida durante la duración del viaje. Los pasajeros en criosueño están confinados en sus camarotes.
    Cabin - El número de cabina donde se hospeda el pasajero. Toma la forma , donde puede ser para babor o para estribor.deck/num/sidesidePS
    Destination - El planeta al que el pasajero desembarcará.
    Age - La edad del pasajero.
    VIP - Si el pasajero ha pagado por un servicio VIP especial durante el viaje.
    RoomService, , , , , - Cantidad que el pasajero ha facturado en cada una de las muchas comodidades de lujo de la nave espacial Titanic.FoodCourtShoppingMallSpaVRDeck
    Name - El nombre y apellido del pasajero.
    Transported - Si el pasajero fue transportado a otra dimensión. Este es el objetivo, la columna que está tratando de predecir.
    test.csv - Registros personales del tercio restante (~4300) de los pasajeros, que se utilizarán como datos de prueba. Su tarea es predecir el valor de para los pasajeros de este conjunto. Transported

* sample_submission.csv - Un archivo de envío en el formato correcto.
    PassengerId - Identificación de cada pasajero en el equipo de prueba.
    Transported - El objetivo. Para cada pasajero, prediga uno de los dos o .TrueFalse

