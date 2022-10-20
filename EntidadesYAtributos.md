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
- Nombre (**_PK_**)
- Fecha de lanzamiento
- Número de canciones
- Duración
- Artista (**_FK_**)

### Géneros
- id_generos(**_PK_**)
- Nombre
- Descripción

### Países
- id_paises(**_PK_**)
- Nombre
- Clave país
## Relaciones

1. Un **país** poseé **artista** (1-M)
2. Una **canción** tiene **artista** (1-M)
3. Un **albúm** poseé Artista y **canciones**(M-M)
4. Un **género** poseé **canciones** (1-M)


