### Clases:
- Actor
- Pawn
- Character
- Player Controller
- Game Mode Base
- Actor Component
- Scene Component

### Componentes:
- Static Mesh
- Box Collision

##### Eventos:
Los componentes tienen eventos que se pueden utilizar para correr codigo en el Event Graph:
- On Component Begin Overlap

### Variables:
Las variables se arrastran desde el menu de variables y se pueden usar en modo *set* o *get*.
##### Tipos de Variables:
- Int
- Float
- String
- Vector
- Rotator: Funciona como un valor de rotacion.
- Transform: Funciona como un valor de transformacion (location/rotation/scale).

### Nodos:
- **Event Begin Play**
- **Branch**: Revisa si un boolean es verdadero o falso y ejecuta codigo en dependencia de la respuesta.
- **Print String**: Imprime texto en pantalla.
- **Get World Location**: Si se utiliza con el *Capsule Component* devuelve el vector de dicha capsula.
- **Key**: Permite utilizar cualquier boton del teclado para ejecutar una accion cuando se *presiona* o *se deja de presionar*. 
- **Cast to Third Person Character**: Verifica si el objecto es el BP del ThirdPersonCharacter
- **Enable Input**: Habilita el uso de un boton
- **Disable Input**: Deshabilita el uso de un boton
- **Get Player Controller**: