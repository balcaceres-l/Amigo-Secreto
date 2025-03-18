<h1>Amigo Secreto</h1>
Este proyecto permite gestionar un sorteo de "Amigo Secreto" donde los participantes ingresan sus nombres y el sistema elige un ganador al azar.

<h2>Funcionalidades</h2> 

- Agregar amigos: Permite ingresar nombres válidos sin repetir.

- Validaciones: Solo se permiten letras, no números ni caracteres especiales.

- Lista de participantes: Muestra los nombres ingresados.

- Sorteo aleatorio: Selecciona un amigo y lo elimina de la lista.

- Interfaz dinámica: Se actualiza automáticamente la lista y el botón de sorteo se habilita/deshabilita según la cantidad de participantes.

<h2>Archivos</h2>

- index.html: Contiene la estructura de la página.

- app.js: Lógica de funcionamiento del sorteo.

<h2>Descripción de Funciones</h2>

- agregarAmigo()

Obtiene el valor del input y valida que solo contenga letras.

Verifica que el nombre no esté repetido en la lista.

Agrega el nombre al array amigos y lo muestra en la lista de la página.

Limpia el input después de agregar el nombre.

Habilita el botón de sorteo si hay al menos 3 amigos registrados.

- sortearAmigo()

Verifica que haya al menos 3 amigos en la lista.

Selecciona un amigo al azar, lo elimina del array y actualiza la lista.

Muestra el nombre seleccionado en el título principal (h2).

Deshabilita el botón de sorteo si quedan menos de 3 amigos.

- actualizarLista()

Borra la lista actual en el HTML.

Recorre el array amigos y actualiza la lista en la interfaz.
