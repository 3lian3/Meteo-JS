### Application Météo :sunny: :cloud: :umbrella:

### Description

Ce projet est une application météo construite en JavaScript pur. Il utilise l'API OpenWeather pour récupérer les données météorologiques et les afficher dans l'application. Le projet utilise des fonctionnalités modernes de JavaScript telles que `async/await` pour gérer les requêtes API et implémente également une gestion des erreurs robuste.

### :hammer_and_wrench: Technologies utilisées

- JavaScript (ES6+)
- API OpenWeather
- HTML5
- CSS3

### :white_check_mark: Prérequis

- Navigateur moderne supportant ES6 (comme Chrome, Firefox)
- Clé API d'OpenWeather

### :gear: Installation

1. Clonez ce dépôt GitHub.
2. Ouvrez le fichier `index.html` dans votre navigateur.
3. Insérez votre clé API OpenWeather dans le fichier `script.js`.

### :book: Utilisation

Après avoir inséré votre clé API, vous pouvez rechercher la météo par ville ou par géolocalisation.

**Exemple d'utilisation du code pour récupérer les données météo :**

```javascript
async function fetchWeather(city) {
    try {
        const response = await fetch(`API_URL_HERE${city}API_KEY_HERE`);
        const data = await response.json();

        // Utilisation des données
    } catch (error) {
        // Gestion des erreurs
    }
}
```
