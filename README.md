# IA
Intel·ligència artifical

Estat:
 - quins son els conductors
 - distancia recorreguda pel conductor
 - qui recull i en quin ordre ho fa
 - totes les persones han estat recullides -> vector de bools - operador de move - qui falta per agafar, estan tots agafats

ArrayList<bool> estaRecullit
CONSULTA:
    estaRecullit(int indexPersona);


ArrayList<pair<dist,arrayList> > conductors
CONSULTA:
    getKm(int index);
    getOrder(); //return arrayList


Operador
 - moure passatger - deixar persona
 - intercambiar persones de dos cotxes
 - intercambiar persones entre el mateix cotxe -> buscar algun ordre vàlid més eficient per millorar la distància
 - afegir persona
 - deixar persona
