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


