# Pruebas1.0
retos del grupo de estudio
    reto terminado, el primer commit creado indica donde se agrego el box-shadow y border-radius(header y main) ya que por algun motivo no pude agregar el border radius al container(padre) que tiene el header y main, a continuacion mas detalles.
    Problema1:
        si se le quita border radius a los contenedores hijos(header y main)
        e intenta ponerlo en el contenedor padre que es div(container)
        no ejecutara, debido a eso se le agrego border radius independientemente
        a cada contenedor hijo.
    Problema2:
        Una ves agregamos border radius a los hijos, al intentar agregar border shadow al padre para poder
        tener un sombreado lindo detras del contenedor, las sombras hacen notar los bordes cuadrados del contenedor padre ya que el efecto de border radius de los hijos no causa efecto en el padre.
        "cabe resaltar que tanto el padre es contenedor como los hijos tambien son contenedores, lo hice asi
        ya que con flex es mas facil organizarlos personalmente" 
    PROBLEMA PENDIENTE...
