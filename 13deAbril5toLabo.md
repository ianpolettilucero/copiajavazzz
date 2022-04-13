

1. Tomar la clase Persona creada en clases anteriores y agregarle 
	el método "esUnAdultoJoven" retorne true si la edad de la persona
	es mayor o igual a 18 y menor o igual a 35.

2. Crear la clase Canción que tenga como atributos: "nombre" (una variable de tipo String) y "duraciónEnSegundos" (una variable de tipo int)
   - Agregar un constructor por defecto y un constructor que reciba
   un nombre y una duración expresada en segundos.
   - Agregar un método que se llame "esUnaCancionLarga" que retorne
   true si la canción tiene una duración mayor o igual a 240 segundos.

3. Crear la clase Cantante como subclase de la clase Persona.
	- Agregarle el atributo "nombreArtístico" como variable de
	tipo String y el atributo "canciones" como variable
	de tipo ArrayList que sirva para almacenar objetos de la 
	clase Canción.
	- Agregar un método que se llame "obtenerCancionesMasLargas" 
	que retorne una lista con los nombres de las canciones más largas.
	- Agregar un método que se llame "agregarCanción" que reciba un nombre
	de canción y una duración en segundos.

4. Crear la clase SistemaDeCantantes que tenga como atributo una lista
   de objetos de la clase Cantante llamada "cantantes". 
   - Agregar un constructor por defecto.
   - Agregar un método llamado "obtenerCantantesJovenes" que retorne un
   ```ArrayList<Cantante>``` que contenga a los cantantes que tienen una edad entre 18 y 35. 
   - Agregar un método llamado "agregarCancion" que reciba tres parámetros: el nombre artístico del cantante, nombre de la canción y
   la duración de la canción en segundos. Este método deberá agregar una
   nueva canción a la lista de canciones del artista indicado.

5. Crear 1 objeto de la clase Cantante utilizando el constructor por 
   defecto y luego cambiarle el nombre artístico utilizando un "setter".
   Comprobar que el cambio se realizó correctamente utilizando un "getter".
