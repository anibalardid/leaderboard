# Leaderboard

## Descripción
Este proyecto surgió de una necesidad/idea de Alan (@soyelmago).  
La finalidad es tener una página con un ranking de un evento de hackers dinámico.


## Funcionamiento
El Top 3 y el ranking va cambiando dinámicamente cada vez que se cambie el archivo JSON donde se encuentra la info de todos los participantes.


## Configuración
Editar el archivo ranking.json y configurar los datos de cada participante del evento.  
El formato es:  
```json
{
    "avatar": "https://path-imagen.any",
    "name": "Nombre",
    "twitter": "twitteraccount",
    "reports": 11,
    "bounties": 22,
    "reputation": 33
},
```

## Instalación
- Copiar todo el contenido en el directorio que se quiera levantar el ranking.
- Configurar ranking.json
- Cambiar imagen del logo `assets/logo.png`
- Cambiar imagen default de avatar para usuarios sin foto `assets/avatar.png`




