# Pokémon Dashboard en Power BI

¡Bienvenido a mi proyecto de Dashboard de Pokémon en Power BI! Este proyecto utiliza datos extraídos de la PokeAPI para crear un dashboard interactivo que permite visualizar información sobre diferentes Pokémon.

![Captura de Pantalla del Dashboard](images/dashboard.png)

## Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Scripts de Extracción de Datos](#scripts-de-extracción-de-datos)
- [Contribuciones](#contribuciones)
- [Contacto](#contacto)

## Descripción del Proyecto

Este proyecto fue creado para explorar mis habilidades en Power BI, DAX, HTML, y CSS. Utiliza la PokeAPI para obtener datos de Pokémon y presenta un dashboard interactivo que muestra estadísticas, evoluciones y otros detalles de cada Pokémon.

## Instalación

Para ejecutar este proyecto localmente, sigue los siguientes pasos:

1. Clona este repositorio:
   
   ```bash
   git clone https://github.com/injantedataweb/pokemon-dashboard.git
   
## Uso

Una vez que el dashboard esté abierto en Power BI, podrás:
- Ver estadísticas base de cada Pokémon, como HP, ataque, defensa, ataque especial, defensa especial, velocidad y el total.
- Ver el peso (kg) y la altura (m) de cada Pokémon.
- Explorar las cadenas de evolución de los Pokémon.
- Filtrar Pokémon por generación, categoría y tipo.

## Scripts de Extracción de Datos

- extract_base.py: Este script se encarga de extraer la información básica de cada Pokémon y genera un archivo CSV (pokemon_base.csv). El archivo contiene su identificador, el nombre, el tipo, enlace de la imagen, las estadísticas base, el peso y la altura.
- extract_evolution.py: Este script obtiene la información evolutiva de cada Pokémon y genera un archivo CSV (pokemon_evolution.csv). Incluye datos sobre el nombre del Pokémon, su grupo de evolución y la fase de evolución. Este archivo se utiliza para mostrar las cadenas evolutivas en el dashboard de Power BI.
- extract_types.py: Este script extrae información sobre los tipos de Pokémon y genera un archivo CSV (pokemon_types.csv). El archivo contiene datos sobre cada Pokémon que separa su tipo primario y secundario en fila independiente con su combicación de tipos,lo que permite filtrar y visualizar Pokémon que poseen un tipo particular, ya sea como tipo primario o secundario, en el dashboard de Power BI.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, siéntete libre de abrir un issue o un pull request en este repositorio.

## Contacto

LinkedIn: TuNombre

¡Gracias por visitar mi proyecto!
