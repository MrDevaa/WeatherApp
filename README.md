## Projet Vue WeatherApp est en cours de développement...


Ce modèle vous aide à démarrer le développement avec Vue 3 en utilisant Vite.

## Configuration IDE Recommandée
Pour une meilleure expérience de développement, nous recommandons d'utiliser :
- **VSCode** avec l'extension **Volar** (et désactiver Vetur).

## Personnalisation de la Configuration
Pour des options de configuration détaillées, consultez la [Référence de Configuration Vite](https://vitejs.dev/config/).

## Installation du Projet
Commencez par installer les dépendances :

## npm install

### Compilation et Rechargement à Chaud pour le Développement
Pour démarrer un serveur de développement local avec rechargement à chaud :

## npm run dev

### Compilation et Minification pour la Production
Pour déployer votre projet en production :

## npm run build

## Utilisation des API
### API Météo
Pour récupérer les données météorologiques, vous avez besoin d'une clé API de [OpenWeather](https://openweathermap.org/api/one-call-api).

Exemple d'utilisation de l'API :
```javascript
// Exemple d'utilisation de l'API OpenWeatherMap
const apiKey = 'votre_clé_api_ici';
const apiUrl = `https://api.openweathermap.org/data/2.5/onecall?lat={lat}&lon={lon}&exclude={part}&appid=${apiKey}&units=metric`;
fetch(apiUrl)
  .then(response => response.json())
  .then(data => console.log(data));
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
## API Cartographie
Pour la géocodification et les cartes, vous aurez besoin d'une clé API de Mapbox.

Ressources Supplémentaires
Documentation de l'API OpenWeatherMap
Documentation de l'API Mapbox
Guide Vue Suspense
Icônes Font Awesome
