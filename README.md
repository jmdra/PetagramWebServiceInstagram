# Petagram Web Service
Tarea de Web Services entre Instagram y Petagram, de la Semana 1 del Curso 4.
Para ver la Demostración en Youtube de la App: https://www.youtube.com/watch?v=xUfRwdXxUeE

En la Primer Pantalla se observa el primer fragment con el Timeline, aqui se utilizaron los siguiente endpoints:

Para Obtener los usuarios que se estan siguiendo y se guardan en un arreglo
https://api.instagram.com/v1/users/self/follows?access_token=ACCESS-TOKEN

Para Obtener la Recent Media de los usuarios que se guardaron en el arreglo
https://api.instagram.com/v1/users/{user-id}/media/recent/?access_token=ACCESS-TOKEN
[![Pantalla 1](https://github.com/jmdra/PetagramWebServiceInstagram/blob/master/petagramws1.png)](#Pantalla)

En la Segunda pantalla observamos el segundo fragment, con la Foto de perfil de la cuenta base y sus fotos subidas con likes, aquí se utilizarón los siguientes endpoints:
https://api.instagram.com/v1/users/{user-id}/media/recent/?access_token=ACCESS-TOKEN
[![Pantalla 1](https://github.com/jmdra/PetagramWebServiceInstagram/blob/master/petagramws2.png)](#Pantalla)

En la Tercer Imagen vemos el Toolbar con las Opciones de Contacto que nos lleva a enviar un correo y Acerca de con biografia del Desarrollador y a Cambiar la Cuenta para mostrar el Perfil.
[![Pantalla 1](https://github.com/jmdra/PetagramWebServiceInstagram/blob/master/petagramws3.png)](#Pantalla)

La cuenta que ingreses se guarda en una shared preferences y se utiliza el siguiente endpoint para volver a obtener los datos de la cuenta guardada recientemente
https://api.instagram.com/v1/users/{user-id}/media/recent/?access_token=ACCESS-TOKEN
[![Pantalla 1](https://github.com/jmdra/PetagramWebServiceInstagram/blob/master/petagramws4.png)](#Pantalla)
[![Pantalla 1](https://github.com/jmdra/PetagramWebServiceInstagram/blob/master/petagramws5.png)](#Pantalla)




