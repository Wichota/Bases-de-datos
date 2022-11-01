## Países 
-  [Información País](https://gist.github.com/brenes/1095110)


# Entidades y atributos

## Música

### Artistas
- id_artista (**_PK_**)
- Nombre
- Fecha de nacimiento
- Nacionalidad
- id_pais(**_FK_**)


### Canciones
- id_cancion(**_PK_**)
- Nombre
- Género(**_FK_**)
- Fecha de lanzamiento
- Album (**_FK_**)

### Albumes
- id_albumes(**_PK_**)
- Nombre 
- Fecha de lanzamiento
- Número de canciones
- Duración
- Artista (**_FK_**)

### Género
- id_genero(**_PK_**)
- Nombre
- Descripción

### Países
- id_paises(**_PK_**)
- Nombre
- Dominio 

## Relaciones

1. Un **país** poseé **artista** (1-M)
2. Una **canción** tiene **artista** (1-M)
3. Un **albúm** poseé Artista y **canciones**(M-M)
4. Un **género** poseé **canciones** (1-M)

![Luisa Soriano](https://cdn.discordapp.com/attachments/1011284720350412802/1035211208820789299/Modeldrawio.png)

-----------

## Reglas de negocio
 
 **Artistas**

 1. Crear un artista
 1. Leer todos los artistas
 1. Leer un artista en particular
 1. Leer todos los artistas de un país
 1. Actualizar un artista
 1. Eliminar un artista

 **Canciones**

 1. Crear una canción
 1. Leer todas las canciones
 1. Leer una canción en particular
 1. Leer todas las canciones de un género
 1. Leer todos las canciones de un album 
 1. Actualizar una canción
 1. Eliminar una canción

 **Albumes**

 1. Crear un album 
 1. Leer todos los albumes 
 1. Leer un album en particular
 1. Leer todos los albumes de un artista
 1. Actualizar un album
 1. Eliminar un album

 **Género** 
 1. Crear un género
 1. Leer todos los géneros
 1. Leer un género en particular 
 1. Actualizar un género
 1. Eliminar un género

 **País** 

1. Crear un pais.
1. Leer todos los paises.
1. Leer un país en particular.
1. Actualizar un país.
1. Eliminar un país.


