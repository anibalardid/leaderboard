# Leaderboard

## Descripción
Este proyecto surgió de una necesidad/idea de Alan (<a href="https://twitter.com/soyelmago">@soyelmago</a>) y el team Bug Bounty Argentina (<a href="https://twitter.com/bugbounty_space">@bugbounty_space</a>).  
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

El orden de los participantes se realizará automático basándose en la reputación.  


## Instalación
- Copiar todo el contenido en el directorio que se quiera levantar el ranking.
- Configurar ranking.json
- Cambiar imagen del logo `assets/logo.png`
- Cambiar imagen default de avatar para usuarios sin foto `assets/avatar.png`


## Authors
Bug Bounty Argentina  
<a href="https://twitter.com/bugbounty_space" ><img src="https://img.shields.io/twitter/follow/bugbounty_space.svg?style=social" /> </a>

Anibal Ardid  
<a href="https://twitter.com/aardid" ><img src="https://img.shields.io/twitter/follow/aardid.svg?style=social" /> </a>
  
Alan Levy  
<a href="https://twitter.com/soyelmago" ><img src="https://img.shields.io/twitter/follow/soyelmago.svg?style=social" /> </a>
  
