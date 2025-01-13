# Airbnb-Santiago-Chile-2024-dashboard
__Creación de un dashboard interactivo en Tableau sobre el mercado de Airbnb en Santiago, Chile__

<image src="https://github.com/BastianLQ/Airbnb-Santiago-Chile-2024-dashboard/blob/main/Images/dashboard.jpg" alt="Dashboard">
  
_Captura de pantalla del dashboard, para ver en Tableau hacer click [aquí](https://public.tableau.com/app/profile/basti.n.l.pez/viz/TendenciasenYoutube/TendenciasenYouTube)_

## Descripción del proyecto
Este dashboard contiene información sobre el mercado de Airbnb en la región metropolitana de Chile, principalmente, sobre los precios por ubicación y las reviews dejadas por los usuarios. Está inspirado en un trabajo del creador de contenido "DataScience RoadMap" en el que analiza el mercado de la plataforma de hosting para la ciudad de Nueva York.

## Proceso del proyecto
- Se descargaron los datos de la [web](https://insideairbnb.com/get-the-data/).
- Revisando los datos, me percaté de que el campo "Neighborhood Group" (grupo de barrios o sector) estaba vacío, por ende se averiguó la disposición de las comunas y se clasificaron en siete sectores diferentes:
  - __Sector nororiente:__ Las Condes, Providencia, Vitacura, La Reina, Ñuñoa y Lo Barnechea.
  - __Sector centro:__ Santiago, Estación Central, Quinta Normal, Independencia y Recoleta.
  - __Sector poniente:__ Maipú, Cerrillos, Pudahuel, Lo Prado, Renca, Cerro Navia.
  - __Sector sur:__ Pedro Aguirre Cerda, San Joaquín, San Miguel, San Bernardo, Lo Espejo, La Cisterna, La Granja, Puente Alto, La Florida, La Pintana, El Bosque y San Ramón.
  - __Sector suroriente:__ Peñalolén, Macul, La Granja y Pirque.
  - __Sector norte:__ Colina, Huechuraba, Quilicura, Lampa, Tiltil, Conchalí.
- Se categorizaron los datos (`listings.csv`) usando python y jupyter notebooks, y se creó un nuevo dataset llamado `airbnb_stgo.csv` con los datos optimizados.
- Con los nuevos datos se construyó el dashboard.
